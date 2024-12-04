<script>
  let { children } = $props();
</script>

<span class="text-lg sm:text-xl font-semibold transition-all text-indigo-500">
  <span> {@render children?.()} </span>
</span>
