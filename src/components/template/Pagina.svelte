<script>
	import Aside from './Aside.svelte';
	import Footer from './Footer.svelte';
	import Header from './Header.svelte';

	let { children } = $props();
</script>

<div class="flex min-h-screen flex-col bg-black text-white">
	<Header />
	<div class="mx-auto flex w-full max-w-7xl flex-1 p-5">
		<Aside />
		<main class="flex-1">
			{@render children?.()}
		</main>
	</div>
	<Footer />
</div>
