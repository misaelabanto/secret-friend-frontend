<script lang="ts">
  import Input from '../components/input.svelte';
  import { InputType } from '../interfaces/input-type.interface';
</script>

<div>
  <Input
    id='room-name'
    label='Nombre de la sala'
    placeholder='Nombre de la sala'
    type={InputType.text}
  />
</div>

<style></style>