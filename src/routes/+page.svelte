<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconMessageSquare from "~icons/lucide/message-square";
	import IconZap from "~icons/lucide/zap";
	import IconShieldCheck from "~icons/lucide/shield-check";
	import IconUserPlus from "~icons/lucide/user-plus";
	import IconNetwork from "~icons/lucide/network";
	import IconTrendingUp from "~icons/lucide/trending-up";
</script>

<Hero
	centered={false}
	title="Transform scattered expertise into instant answers"
	subtitle="Capture knowledge directly from your experts and deliver structured responses across teams, without disrupting daily operations."
	imageSrc="/generated/image-a-professional-hr-director-dressed-in-bu.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Get started"
		},
		{
			href: "/about",
			label: "Learn more"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/siemens.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/sap.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bosch.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/mercedes-benz.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Expertlift AI solves the critical problem of knowledge loss when employees leave by capturing expertise through natural conversation during daily work. We serve HR directors and operations leaders at mid-sized manufacturing and professional services firms who need to onboard faster and retain institutional knowledge. Our platform delivers structured answers across teams without requiring manual documentation, addressing the skilled worker shortage that threatens operational continuity."
/>

<Testimonials
	testimonials={[
		{
			name: "Kristina Bergmann",
			position: "HR Director",
			company: "Schäfer Werkzeugbau",
			quote:
				"Expertlift reduced our onboarding time from 6 weeks to just 10 days. New hires now access 20 years of machining expertise instantly, and we've eliminated the panic when senior staff take vacation.",
			image: "/generated/image-confident-german-female-hr-director-with.webp"
		},
		{
			name: "Matthias Keller",
			position: "COO",
			company: "Hoffmann Maschinenbau",
			quote:
				"We saved over €120,000 in the first year by preventing costly mistakes. When our lead engineer retired, his expertise stayed with us instead of walking out the door.",
			image: "/generated/image-german-male-coo-with-strong-executive-pr.webp"
		},
		{
			name: "Sabine Richter",
			position: "Operations Manager",
			company: "Fischer Präzisionstechnik",
			quote:
				"Knowledge capture happens naturally during daily work, no extra documentation required. Our team actually uses it because the AI delivers answers in under 3 seconds, exactly when they need them.",
			image: "/generated/image-approachable-german-female-operations-ma.webp"
		}
	]}
/>

<Features
	title="Capture, access, and scale expert knowledge"
	subtitle="Built for teams that can't afford to lose critical expertise when employees leave"
	features={[
		{
			title: "Capture expertise without disruption",
			description:
				"Extract knowledge through natural conversations during daily work instead of requiring manual documentation that employees never complete.",
			icon: IconMessageSquare
		},
		{
			title: "Instant access to structured answers",
			description:
				"Transform scattered expertise into organized, searchable responses that teams can find in seconds, not hours.",
			icon: IconZap
		},
		{
			title: "Retain knowledge when employees leave",
			description:
				"Preserve critical institutional knowledge before experts retire or transition, eliminating the costly knowledge gaps that cripple operations.",
			icon: IconShieldCheck
		},
		{
			title: "Onboard new employees faster",
			description:
				"Reduce training time by giving new hires immediate access to expert knowledge and best practices without overwhelming senior staff.",
			icon: IconUserPlus
		},
		{
			title: "Connect expertise across teams",
			description:
				"Break down silos by making expert knowledge accessible to every department, ensuring consistency and quality throughout the organization.",
			icon: IconNetwork
		},
		{
			title: "Scale knowledge operations efficiently",
			description:
				"Grow from 100 to 500,000 employee seats without exponentially increasing training costs or knowledge management overhead.",
			icon: IconTrendingUp
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Stop losing expertise when employees walk out the door"
	subtitle="Start capturing knowledge today"
	description="Your senior experts hold decades of critical knowledge. Every retirement, resignation, or transition puts your operations at risk. Expertlift captures this expertise through natural conversation during daily work, so institutional knowledge stays with your company, not with individuals. Join mid-sized firms who've reduced onboarding time by 75% and eliminated costly knowledge gaps."
	imageSrc="/generated/image-a-professional-hr-director-well-dressed-.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Schedule a demo",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>
