<script>
  import Description from "./Item/Description.svelte";
  import Label from "./Item/Label.svelte";
  import LabelTime from "./Item/LabelTime.svelte";
</script>

<div class="p-4 flex flex-col items-center sm:items-start">
  <slot {Label} {LabelTime} {Description} />
</div>
