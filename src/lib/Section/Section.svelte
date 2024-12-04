<script>
  import Name from "./Name.svelte";
  import Item from "./Item.svelte";
</script>

<div class="sm:w-[32rem]">
  <slot {Name} {Item} />
</div>
