<script lang="ts">
	import Button from './components/button.svelte';
	import Input, { InputType } from './components/input.svelte';
</script>

<main>
	<h1>Generador de Amigo Secreto</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<Button text='Crear sala' color='green'/>
	<Button text='Unirme a una sala' color='blue'/>
	<br>
	<Input
		id="room-name"
		placeholder='hello'
		type={InputType.text}
		label='Nombre de la sala'
	/>
</main>

<style windi:preflights:global windi:safelist:global>
	body {
		@apply p-8;
	}
	h1 {
		@apply text-2xl;
	}
</style>