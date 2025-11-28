<script lang="ts">
	import './layout.css';
	import Header from '$lib/Header.svelte';
	
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href="/logo.png" />
</svelte:head>

<Header/>

{@render children()}
