<script>
  import Section from "./Section/Section.svelte";
</script>

<Section let:Name let:Item>
  <Name>Skills</Name>
  <Item let:Label let:Description>
    <Label>Backend</Label>
    <Description>Go, Javascript</Description>
    <Description>Echo, NodeJS, Express, NestJS, MongoDB, PostgreSQL</Description>
  </Item>
  <Item let:Label let:Description>
    <Label>Frontend</Label>
    <Description>HTML, CSS, SCSS, Javascript, Typescript</Description>
    <Description>Angular, SvelteJS, TailwindCSS, Material UI</Description>
  </Item>
  <Item let:Label let:Description>
    <Label>English</Label>
    <Description>Upper intermediate</Description>
  </Item>
</Section>
