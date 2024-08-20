<script>
	import Head from '$lib/head.svelte';
	import Navbar from '$lib/navbar.svelte';
	import Hero from '$lib/hero.svelte';
	import Projects from '$lib/projects.svelte';
	import Design from '$lib/design.svelte';
    import Footer from '$lib/footer.svelte';
	import '../styles/app.css';
</script>

<Head />

<div class="index">
	<Navbar />
	<Hero />
	<Projects />
	<Design />
    <Footer />
</div>
