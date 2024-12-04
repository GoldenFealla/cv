<script>
  // Section Components
  import Section from "./Section/Section.svelte";
</script>

<div>
  <Section let:Name let:Item>
    <Name>Project</Name>
    <Item let:Label let:LabelTime let:Description>
      <LabelTime>
        {#snippet text()}
          Gear Commerce
        {/snippet}
        {#snippet time()}
          08/2024 - now
        {/snippet}
      </LabelTime>
      <Label>Web Developer</Label>
      <Label>Angular, Go, PostgreSQL, Redis, Cloudflare</Label>
      <Description>Number of Participants 1 (self taught)</Description>
      <Description
        >Making a ecommerce website using current knowledge and challenge with large project</Description
      >
      <Description>
        Website:
        <a class="underline" href="https://gear.goldenfealla.dev">gear.goldenfealla.dev</a>
      </Description>
      <Description>
        Angular for frontend:
        <a class="underline" href="http://github.com/GoldenFealla/gear-ecommerce-frontend">Github</a
        >
      </Description>
      <Description>
        Go for backend:
        <a class="underline" href="https://github.com/GoldenFealla/gear-ecommerce-backend">Github</a
        >
      </Description>
    </Item>
  </Section>
</div>
