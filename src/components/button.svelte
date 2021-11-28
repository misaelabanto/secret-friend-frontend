<script lang="ts">
  export let text = '';
  export let color = '';
</script>

<button class={color}>
  {text}
</button>

<style>
  .blue {
    @apply h-10 w-40 bg-blue-500 text-white;
  }
  .green {
    @apply h-10 w-40 bg-green-500 text-white;
  }
</style>
