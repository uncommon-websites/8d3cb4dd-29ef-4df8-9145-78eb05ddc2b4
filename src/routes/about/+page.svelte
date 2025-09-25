<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
		}
	];
</script>

<SecondaryHero
	title="Focus, not frenzy"
	subtitle="Quiet the noise, hear what matters"
	imageSrc="/generated/image-a-diverse-professional-team-collaboratin.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"The inspiration behind Brief Me came from a simple but painful truth: even the most focused leaders were drowning under an endless stream of communication. Between Slack, email, calendars, and chat threads, most executives were spending over three hours a day just trying to catch up — not strategize, not lead, just catch up. Important decisions got buried under notifications, and the overwhelm always seemed to outpace the inbox zero attempts.",
		"Rather than ask leaders to manage one more app, we built Brief Me to work around their lives — not the other way around. With AI-powered filtering and professional audio narration, we turn your digital noise into clarity you can act on. Every brief highlights the decisions, deadlines, and updates that truly matter. Delivered daily in your podcast app, inbox, or on your commute. In early testing, our users saved an average of 7.2 hours per week — not by doing more, but by hearing less, better.",
		"Our mission is clear: give leaders back their time, attention, and ability to think clearly. No dashboards, no hopping between apps — just focused, actionable briefings that reduce stress and increase impact. Hundreds of startup leaders are already listening. We're just getting started."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to reclaim your focus?"
	subtitle="Join hundreds of startup leaders already listening"
	description="Transform your information overload into focused productivity with Brief Me's intelligent audio briefings."
/>
