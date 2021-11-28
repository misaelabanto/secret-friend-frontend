<script lang="ts">
	import { Router, Route } from 'svelte-navigator';
	import Create from './pages/create.svelte';
	import Index from './pages/index.svelte';
</script>

<Router>
	<main>
		<Route path='/'>
			<Index />
		</Route>
		
		<Route path='create'>
			<Create />
		</Route>
	</main>
</Router>

<style windi:preflights:global windi:safelist:global>
	body {
		@apply p-8;
	}
	h1 {
		@apply text-2xl;
	}
</style>