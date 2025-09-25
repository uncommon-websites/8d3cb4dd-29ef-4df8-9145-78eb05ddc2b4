<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Focus over frenzy",
			description: "We believe attention is precious. Our AI cuts through the noise to deliver only what matters, giving leaders back their ability to think strategically."
		},
		{
			title: "Human-centered intelligence",
			description: "Technology should adapt to how leaders actually work. We build audio-first solutions that fit seamlessly into busy lives, not the other way around."
		},
		{
			title: "Measurable freedom",
			description: "Every feature we build must demonstrably save time and reduce stress. Our users save 7.2 hours weekly—that's time returned to leadership and decision-making."
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

<!-- Team and Investor sections removed - no information available for Brief Me -->

<!-- CTA Section -->
<CallToAction
	title="Hours back. Stress down. Focus locked."
	subtitle="Join 357+ early adopters saving 7.2 hours weekly"
	description="Stop drowning in 400+ daily messages. Brief Me's AI transforms your communication chaos into focused audio briefings you can consume on your commute. Private beta access available now."
	imageSrc="/generated/image-a-premium-documentary-style-photograph-o.webp"
/>
