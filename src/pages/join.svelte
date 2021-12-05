<script lang="ts">
  import Button from '../components/button.svelte';
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
  label='Nombre de usuario'
  placeholder='Nombre de usuario'
  type={InputType.text}
/>
/>
<Button color='blue' text='Continuar'/>

<style></style>