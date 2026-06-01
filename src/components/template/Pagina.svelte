<script>
	import Logo from './Logo.svelte';
</script>

<div class="flex flex-col items-center justify-center gap-4 border-b bg-black text-white">
	<Logo />

	<div class=" flex min-h-screen max-w-7xl flex-1 bg-amber-300 p-5">
		<main class="flex">
			<slot />
		</main>
	</div>
</div>
