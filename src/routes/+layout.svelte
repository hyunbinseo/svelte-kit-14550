<script lang="ts">
	let { children } = $props();
</script>

<svelte:head>
	<title>Hello, World!</title>
</svelte:head>

{@render children?.()}
