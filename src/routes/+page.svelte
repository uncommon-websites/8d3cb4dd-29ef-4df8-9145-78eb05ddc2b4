<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons for features
	import IconHeadphones from "~icons/lucide/headphones";
	import IconBrain from "~icons/lucide/brain";
	import IconNetwork from "~icons/lucide/network";
	import IconClock from "~icons/lucide/clock";
	import IconMessageCircle from "~icons/lucide/message-circle";
	import IconSettings from "~icons/lucide/settings";
</script>

<Hero
	title="Transform 400+ daily messages into focused productivity"
	subtitle="Brief Me intelligently filters your communications into personalized audio briefs, saving busy executives 7.2 hours weekly. Work deeply. Catch up effortlessly."
	imageSrc="/generated/image-a-professional-executive-dressed-in-prem.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders" 
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/airtable.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/figma.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Brief Me transforms overwhelming communication chaos into clarity for senior executives at fast-growing companies. By intelligently filtering 400+ daily messages from Slack, Teams, Gmail, and Outlook, we deliver personalized audio briefs that save leaders an average of 7.2 hours per week. Instead of drowning in notifications, executives can focus on strategic decisions while staying fully informed through our AI-powered audio summaries during commutes or downtime."
/>

<Testimonials
	testimonials={[
		{
			name: "Mei Chen",
			position: "VP of Engineering",
			company: "Quantum Dynamics",
			quote:
				"Brief Me saves me 8.5 hours weekly by converting 300+ daily Slack and email messages into focused 15-minute audio briefs. I can finally focus on strategic decisions instead of inbox archaeology.",
			image: "/generated/image-documentary-style-environmental-portrait.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Chief Operating Officer",
			company: "Nexus Ventures",
			quote:
				"Before Brief Me, I missed critical client escalations buried in 200+ daily messages. Now I catch every important decision point through their intelligent filtering, eliminating costly communication gaps.",
			image: "/generated/image-cinematic-environmental-headshot-of-a-bl.webp"
		},
		{
			name: "Isabella Rodriguez",
			position: "Head of Product",
			company: "Catalyst Labs",
			quote:
				"The audio briefs during my commute transformed dead time into productive catch-up sessions. I stay fully informed across 12 communication channels while maintaining deep work blocks worth $50K+ in focused development time.",
			image: "/generated/image-editorial-style-portrait-of-a-hispanic-w.webp"
		}
	]}
/>

<Features
	title="Why executives choose Brief Me"
	subtitle="Transform communication chaos into strategic focus with our AI-powered audio briefs"
	features={[
		{
			title: "Audio-first intelligence",
			description: "Skip the dashboard fatigue—get your personalized brief delivered as professional audio during your commute, workout, or walk.",
			icon: IconHeadphones
		},
		{
			title: "Smart message filtering",
			description: "Our AI distinguishes critical decisions from noise, automatically surfacing only the 12% of messages that truly need your attention.",
			icon: IconBrain
		},
		{
			title: "Universal integration",
			description: "Connect Slack, Teams, Gmail, and Outlook in minutes—no workflow disruption, no team training required.",
			icon: IconNetwork
		},
		{
			title: "Executive time savings",
			description: "Join the 357+ leaders already saving 7.2 hours weekly by catching up effortlessly instead of drowning in notifications.",
			icon: IconClock
		},
		{
			title: "Context-aware summaries",
			description: "Get the full story, not just raw data—our AI provides narrative coherence that helps you make informed decisions quickly.",
			icon: IconMessageCircle
		},
		{
			title: "Flexible delivery modes",
			description: "Choose from morning briefs, catch-up summaries, or vacation mode—delivered via email, audio, or private RSS feed.",
			icon: IconSettings
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
