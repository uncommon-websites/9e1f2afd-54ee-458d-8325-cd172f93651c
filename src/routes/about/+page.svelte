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
			title: "Speed without compromise",
			description: "We guarantee 48-hour response times because every day matters to your policyholders and your business."
		},
		{
			title: "Reliable partnerships",
			description: "Our vetted contractor network delivers consistent quality, eliminating the uncertainty that delays claims resolution."
		},
		{
			title: "Complete transparency",
			description: "Real-time project tracking gives you full visibility from claim approval to job completion, building trust at every step."
		}
	];
</script>

<SecondaryHero
	title="Faster claims. Happier policyholders."
	subtitle="Insurance-built roofing you can count on"
	imageSrc="/generated/image-a-group-of-diverse-professionals-collabo.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Leadership that delivers."
	subtitle="Transforming insurance claims resolution."
	stakeholders={[
		{
			name: "Matt Fruge",
			position: "Founder & CEO",
			bio: "Leading the transformation of insurance claim resolution through innovative contractor networks and real-time tracking technology.",
			image: "/generated/image-a-professional-headshot-of-a-ceo-in-the-.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to close claims faster?"
	subtitle="See the difference in 48 hours"
	description="Join property insurance carriers who've reduced claim resolution time from weeks to days. Schedule a demo and discover how our vetted contractor network can transform your roof and gutter claims process."
	imageSrc="/generated/image-a-professional-insurance-claims-adjuster.webp"
/>
