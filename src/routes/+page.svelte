<script lang="ts">
	import Header from "$lib/components/Header.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import CategoryGrid from "$lib/components/CategoryGrid.svelte";
	import AboutText from "$lib/components/AboutText.svelte";
	import NewsletterHero from "$lib/components/NewsletterHero.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen flex flex-col">
	<Header />
	
	<main class="flex-grow">
		<Hero />
		<CategoryGrid />
		<AboutText />
		<NewsletterHero />
	</main>

	<Footer />
</div>

