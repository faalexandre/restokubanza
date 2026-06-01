<script>
	import Logo from './Logo.svelte';
</script>

<div class="relative w-screen overflow-hidden border-b border-zinc-800 text-white">
	<img
		src="/rest-bg.jpg"
		alt="Banner"
		class="block h-55 w-screen object-cover sm:h-60 md:h-80 lg:h-105"
	/>

	<div class="absolute inset-0 flex items-center justify-center">
		<Logo />
	</div>
</div>
