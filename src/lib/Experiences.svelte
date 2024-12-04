<script>
  // Section Components
  import Section from "./Section/Section.svelte";
</script>

<div>
  <Section let:Name let:Item>
    <Name>Experience</Name>
    <Item let:Label let:LabelTime let:Description>
      <LabelTime>
        {#snippet text()}
          ITSS Training Service and Solution Ltd
        {/snippet}
        {#snippet time()}
          06/2023 - now
        {/snippet}
      </LabelTime>
      <Label>Backend Developer</Label>
      <Description>Working with Go and MongoDB for serving API</Description>
    </Item>
  </Section>
</div>
