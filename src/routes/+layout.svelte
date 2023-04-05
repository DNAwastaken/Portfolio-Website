<script>
	import '../app.css';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<wrapper class="flex flex-col h-full" style="min-height: 100vh;">
	<Header />
	<slot />
	<footer-wrapper class="mt-auto">
		<Footer />
	</footer-wrapper>
</wrapper>
