<script lang="ts">
	import Logo from '../components/template/Logo.svelte';
	import './layout.css';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" /></svelte:head>
<Logo />
{@render children()}
