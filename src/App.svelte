<script lang="ts">
	import { Router, Route } from 'svelte-navigator';
	import Create from './pages/create.svelte';
	import Index from './pages/index.svelte';
	import Join from './pages/join.svelte';
</script>

<Router>
	<main>
		<Route path='/'>
			<Index />
		</Route>
		
		<Route path='create'>
			<Create />
		</Route>

		<Route path='join'>
			<Join />
		</Route>
	</main>
</Router>

<style windi:preflights:global windi:safelist:global>
</style>