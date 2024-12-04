<script>
  import Divider from "./lib/Divider.svelte";

  import Header from "./lib/Header.svelte";
  import Skills from "./lib/Skills.svelte";
  import Certificate from "./lib/Certificate.svelte";
  import Experiences from "./lib/Experiences.svelte";
  import Project from "./lib/Project.svelte";
  import Activities from "./lib/Activities.svelte";

  let sections = [Header, Skills, Certificate, Experiences, Project, Activities];
</script>

<div class="h-full w-full">
  <div class="h-64"></div>

  {#each sections as Section}
    <div class="flex flex-col items-center">
      <Section />
    </div>
    <Divider />
  {/each}

  <div class="h-64"></div>
  <div class="w-full pb-8 text-center">
    <span class="text-gray-500">© 2024 GoldenFealla</span>
  </div>
</div>
