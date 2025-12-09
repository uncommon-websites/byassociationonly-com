<script lang="ts">
	import Header from "$lib/components/Header.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import CaseStudies from "$lib/components/CaseStudies.svelte";
	import Services from "$lib/components/Services.svelte";
	import ClientGrid from "$lib/components/ClientGrid.svelte";
	import News from "$lib/components/News.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<main class="bg-[#0e0e0e] min-h-screen text-white overflow-x-hidden">
	<Header />
	<Hero />
	<CaseStudies />
	<Services />
	<ClientGrid />
	<News />
	<Footer />
</main>
