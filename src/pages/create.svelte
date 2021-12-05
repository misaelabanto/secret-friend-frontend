<script lang="ts">
  import Input from '../components/input.svelte';
  import Button from '../components/button.svelte';
  import { InputType } from '../interfaces/input-type.interface';
</script>

<Input
  id='room-name'
  label='Nombre de la sala'
  placeholder='Nombre de la sala'
  type={InputType.text}
/>
<Input
  id='player-name'
  label='Nombre de usuario'
  placeholder='Nombre de usuario'
  type={InputType.text}
/>
<Button color='blue' text='Continuar'/>

<style></style>