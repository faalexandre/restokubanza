<script>
	import Footer from './Footer.svelte';
	import Logo from './Logo.svelte';

	let { children } = $props();
</script>

<div class="flex min-h-screen flex-col bg-black text-white">
	<Logo />

	<main class="flex">
		{@render children?.()}
	</main>

	<Footer />
</div>
