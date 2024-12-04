<script>
  // Section Components
  import Section from "./Section/Section.svelte";
</script>

<div>
  <Section let:Name let:Item>
    <Name>Activities</Name>
    <Item let:Label let:LabelTime let:Description>
      <LabelTime>
        {#snippet text()}
          GDSC Chapter Hoa Sen University
        {/snippet}
        {#snippet time()}
          01/2023 - 01/2024
        {/snippet}
      </LabelTime>
      <Label>Tech lead</Label>
      <Description>Organzie online and offline workshop for Git, Angular, Go</Description>
    </Item>
  </Section>
</div>
