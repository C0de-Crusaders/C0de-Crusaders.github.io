<script lang="ts">
	import '../app.css';
	import Navbar from '../lib/Navbar.svelte';
	let { children } = $props();
	let activePage = '';

</script>

<Navbar />
{@render children()}
