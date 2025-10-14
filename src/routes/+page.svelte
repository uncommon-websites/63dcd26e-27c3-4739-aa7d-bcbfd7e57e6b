<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconZap from "~icons/lucide/zap";
	import IconBriefcase from "~icons/lucide/briefcase";
	import IconLayers from "~icons/lucide/layers";
	import IconServer from "~icons/lucide/server";
	import IconShieldCheck from "~icons/lucide/shield-check";
	import IconUsers from "~icons/lucide/users";
</script>

<CenteredTextOnlyHero
	title="Accelerate reliable AI agent development at industrial scale"
	subtitle="Generate diverse real-world simulation environments through spec-driven code generation. Train autonomous agents that mirror real-world complexity with verifiable task completion."
	imageSrc="/generated/image-a-modern-interior-space-with-a-tiled-wal.webp"
/>
<LogoScroller
	label="Trusted by leading AI labs"
	logoUrls={[
		'https://cdn.brandfetch.io/anthropic.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/openai.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/deepmind.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/microsoft.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Building the future of autonomous agents"
	text="Fleet generates diverse, real-world simulation environments where RL researchers at frontier AI labs can train autonomous agents at scale. Through spec-driven code generation, we create environments that mirror real software workflows with verifiable task completion, solving the critical shortage of high-quality training data. This industrialized approach accelerates the path from research to reliable agents that can handle complex, real-world tasks."
/>

<Testimonials
	testimonials={[
		{
			name: "Dr. Priya Mehta",
			position: "Senior RL Researcher",
			company: "Applied Intelligence Lab",
			quote:
				"Fleet reduced our environment creation time from weeks to days. We shipped 12 new evaluation benchmarks in Q1 alone, letting us iterate on agent capabilities 4x faster than before.",
			image: "/generated/image-a-confident-asian-woman-researcher-with-.webp"
		},
		{
			name: "Dr. Arjun Patel",
			position: "Research Lead, Agent Systems",
			company: "Frontier AI Research",
			quote:
				"The spec-driven approach eliminated 80% of our debugging overhead. Our team can now focus on model architecture instead of fixing broken simulation states, cutting our training cycle from 6 weeks to 10 days.",
			image: "/generated/image-a-confident-south-asian-male-researcher-.webp"
		},
		{
			name: "Dr. Maya Johnson",
			position: "Principal Investigator, Autonomous Systems",
			company: "Advanced Computing Institute",
			quote:
				"Fleet's verification functions gave us confidence in our benchmarks. We eliminated false positives in task completion metrics, saving our team 200+ hours per month previously spent on manual validation.",
			image: "/generated/image-a-confident-black-woman-researcher-with-.webp"
		}
	]}
/>

<Features
	title="Built for industrial-scale agent development"
	subtitle="From spec to simulation in minutes, not months"
	features={[
		{
			title: "Spec-driven environment generation",
			description:
				"Transform specifications into production-ready simulation environments at unprecedented speed through automated code generation. Ship diverse training environments faster than any manual development process.",
			icon: IconZap
		},
		{
			title: "Real-world work simulations",
			description:
				"Train agents on environments designed around actual jobs and workflows, not synthetic tasks. Replicate the complexity of real software interactions with verifiable task completion.",
			icon: IconBriefcase
		},
		{
			title: "Scale to thousands of environments",
			description:
				"Infrastructure built to support industrial-scale agent training with diverse, high-quality environments. Go from prototype to production without rebuilding your entire training pipeline.",
			icon: IconLayers
		},
		{
			title: "Hosted platform with complete toolkit",
			description:
				"Focus on training breakthrough agents, not managing infrastructure. Access SDK, API, and evaluation tools through a fully hosted platform designed for RL practitioners.",
			icon: IconServer
		},
		{
			title: "Built-in verification and observability",
			description:
				"Trust your training data with environments that include verification functions and observability tools. Identify and fix capability gaps with precision diagnostics built into every simulation.",
			icon: IconShieldCheck
		},
		{
			title: "Expert annotator network",
			description:
				"Leverage a network of 700k+ expert annotators who ensure environment quality through industrial QA processes. Scale your training data without sacrificing reliability.",
			icon: IconUsers
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start training breakthrough agents today"
	subtitle="Join frontier labs scaling with Fleet"
	description="While competitors spend weeks building environments manually, leading AGI labs are shipping production-ready simulations in days with Fleet. Join Anthropic, OpenAI, and other top labs co-designing the future of agent training. Start with a proof of concept and see why researchers call Fleet's platform the best in the market."
	imageSrc="/generated/image-a-confident-researcher-celebrating-a-bre.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Request a demo",
			variant: "primary"
		},
		{
			href: "/documentation",
			label: "Explore documentation",
			variant: "secondary"
		}
	]}
/>
