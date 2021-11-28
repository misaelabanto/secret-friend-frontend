<script>
  import { Link } from 'svelte-navigator';
  import Button from '../components/button.svelte';
</script>

<div class="grid">
  <h1>Generador de Amigo Secreto</h1>
  <Link to="create">
    <Button text='Crear sala' color='green'/>
  </Link>
  <Link to="join">
    <Button text='Unirme a una sala' color='blue'/>
  </Link>
</div>

<style>
	h1 {
		@apply text-2xl;
	}
</style>