<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	centered={true}
	title="Restore storm-damaged properties in record time"
	subtitle="Transform insurance claims with our nationwide contractor network and real-time project tracking technology."
	customers={[
		{
			name: "Robert Mitchell",
			position: "Claims Director, Regional Insurance",
			imageSrc: "/generated/image-professional-middle-aged-businessman-in-.webp"
		},
		{
			name: "Sarah Chen",
			position: "Property Claims Manager, State Farm",
			imageSrc: "/generated/image-professional-businesswoman-in-office-att.webp"
		},
		{
			name: "Michael Thompson",
			position: "Senior Claims Adjuster, Allstate",
			imageSrc: "/generated/image-professional-mature-man-in-business-casu.webp"
		},
		{
			name: "Jennifer Davis",
			position: "Claims Operations Director, Travelers",
			imageSrc: "/generated/image-professional-woman-executive-in-a-tailor.webp"
		},
		{
			name: "David Rodriguez",
			position: "Property Claims Supervisor, Liberty Mutual",
			imageSrc: "/generated/image-professional-businessman-with-glasses-in.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/statefarm.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/allstate.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/travelers.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/libertymutual.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Amanda Rodriguez",
			position: "Senior Claims Adjuster",
			company: "American Family Insurance",
			quote:
				"We reduced our average claim resolution time from 45 days to just 6 days. The real-time tracking dashboard gives us complete visibility into every project stage, and contractors actually show up when they say they will.",
			image: "/generated/image-a-confident-female-insurance-claims-adju.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Claims Director",
			company: "Nationwide Insurance",
			quote:
				"The 48-hour response guarantee has been a game-changer for our storm season operations. We've processed 300% more claims this quarter while maintaining customer satisfaction scores above 95%.",
			image: "/generated/image-a-professional-male-insurance-executive-.webp"
		},
		{
			name: "Elena Nakamura",
			position: "Property Claims Manager",
			company: "Farmers Insurance",
			quote:
				"Their contractor network saved us over $2.3 million in expedited repair costs last year. No more emergency contractor markups or delayed settlements - just reliable, vetted professionals who deliver quality work on time.",
			image: "/generated/image-a-confident-female-insurance-claims-mana.webp"
		}
	]}
/>

<Features
	title="Accelerate claim resolution with proven technology"
	subtitle="Transform your insurance claims process with our nationwide contractor network and real-time project tracking that delivers results in days, not weeks."
	features={[
		{
			title: "48-hour response guarantee",
			description: "Get qualified contractors on-site within 48 hours, eliminating the 30-60 day delays that frustrate adjusters and policyholders.",
			imageSrc: "/generated/image-a-professional-contractor-wearing-a-blue.webp"
		},
		{
			title: "Real-time project tracking",
			description: "Monitor every project milestone through our live dashboard that provides complete visibility from initial assessment to final completion.",
			imageSrc: "/generated/image-a-group-of-professionals-including-an-in.webp"
		},
		{
			title: "Nationwide contractor network",
			description: "Access our vetted network of 10,000+ contractors across all 50 states, ensuring coverage even in the most storm-affected regions.",
			imageSrc: "/generated/image-a-wide-angle-view-of-a-peaceful-resident.webp"
		},
		{
			title: "Insurance carrier integration",
			description: "Seamlessly integrate with your existing claims systems to streamline workflows and reduce administrative overhead by 60%.",
			imageSrc: "/generated/image-an-insurance-adjuster-and-a-contractor-s.webp"
		},
		{
			title: "Storm damage specialization",
			description: "Leverage our expertise in roof and gutter repairs from hail, wind, and water damage with contractors trained specifically for insurance claims.",
			imageSrc: "/generated/image-a-recently-storm-damaged-house-is-now-su.webp"
		},
		{
			title: "Quality assurance program",
			description: "Every project includes comprehensive inspections and warranty coverage, giving you confidence in completed repairs and satisfied policyholders.",
			imageSrc: "/generated/image-a-contractor-and-an-insurance-adjuster-c.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
