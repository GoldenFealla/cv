<script>
  let { children } = $props();
</script>

<span class="text-center sm:text-left text-base sm:text-lg transition-all">
  <span class="mr-1 hidden sm:inline-block">•</span>
  <span> {@render children?.()} </span>
</span>
