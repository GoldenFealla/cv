<script>
  let { text, time } = $props();
</script>

<span class="flex flex-col items-center sm:items-start font-semibold mb-5">
  <span class="text-lg sm:text-xl transition-all text-indigo-500"> {@render text?.()} </span>
  <span class="text-sm sm:text-base text-gray-500 transition-all"> {@render time?.()} </span>
</span>
