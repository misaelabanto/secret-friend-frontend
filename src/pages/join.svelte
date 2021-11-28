<script lang="ts">
  import Input from '../components/input.svelte';
  import { InputType } from '../interfaces/input-type.interface';
</script>

<Input
  id='room-name'
  label='Código de la sala'
  placeholder='Código de la sala'
  type={InputType.text}
/>
<Input
  id='player-name'
  label='Nombre'
  placeholder='Nombre'
  type={InputType.text}
/>

<style></style>