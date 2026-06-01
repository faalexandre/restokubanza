<script lang="ts">
	let { name, href = '' } = $props();
</script>

<div>
	li
	<a
		{href}
		class="block rounded-md px-3 py-2 text-sm text-zinc-700 hover:bg-zinc-100 hover:text-zinc-900"
	><span class="font-medium">{name}</span
	</a>
</div>
