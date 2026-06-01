<script lang="ts">
	let { children, title = '' } = $props();
	import DraftsIcon from '@iconify-svelte/material-symbols/drafts';
</script>

<div class="flex flex-col gap-3">
	<span class="text-sm font-bold text-zinc-500"
		>{title}<DraftsIcon class="inline-block h-4 w-4 align-middle" /></span
	>
	<ul class="flex flex-col">
		{@render children?.()}
	</ul>
</div>
