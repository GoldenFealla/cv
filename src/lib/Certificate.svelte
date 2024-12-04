<script>
  // Section Components
  import Section from "./Section/Section.svelte";
</script>

<div>
  <Section let:Name let:Item>
    <Name>Certificate</Name>
    <Item let:Label let:LabelTime let:Description>
      <LabelTime>
        {#snippet text()}
          ITPEC Fundamentals of Engineering Certification (FE)
        {/snippet}
        {#snippet time()}
          2023
        {/snippet}
      </LabelTime>
    </Item>
  </Section>
</div>
