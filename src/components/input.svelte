<script context="module" lang="ts">
  export enum InputType {
    number = 'number',
    phone = 'phone',
    email = 'email',
    text = 'text',
  };
</script>
<script lang="ts">
  export let id = '';
  export let label = '';
  export let placeholder = '';
  export let type: InputType; 
</script>

<label
  class='bg-gray-300 p-3'
  for={id}
>{label}</label>
<input
  class='p-3 border'
  id={id}
  placeholder={placeholder}
  label={label}
  type={type}
/>

<style>
</style>