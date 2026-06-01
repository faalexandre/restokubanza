<script lang="ts">
	import Pagina from '../components/template/Pagina.svelte';
	import './layout.css';
	let { children } = $props();
</script>

<svelte:head><link rel="icon" /></svelte:head>
<Pagina>
	{@render children()}
</Pagina>
