<script lang="ts">
  import Mail from "virtual:icons/lucide/mail";

  import Github from "virtual:icons/logos/github-icon";
  import LinkedIn from "virtual:icons/logos/linkedin-icon";
</script>

<div>
  <div class="w-52 h-52 sm:w-64 sm:h-64 rounded-full border-8 transition-all">
    <img
      class="h-full w-full object-cover object-center rounded-full"
      src="./avatar.jpg"
      alt="avatar"
    />
  </div>
</div>
<div class="mt-5">
  <h1 class="text-2xl sm:text-3xl text-center font-bold transition-all text-indigo-700">
    NGUYEN LE QUOC KHANH
  </h1>
  <h2 class="text-xl sm:text-2xl text-center transition-all">Web Developer</h2>
</div>
<div class="mt-2 sm:mt-5">
  <div class="flex flex-col">
    <span class="flex flex-row items-center">
      <Mail width="20" height="20" class="mr-2" />
      <span class="text-sm sm:text-base"> khanh.nguyenlequoccs@gmail.com </span>
    </span>
    <div class="flex flex-row items-center justify-center mt-5">
      <a class="mx-2" href="https://github.com/goldenfealla">
        <Github width="28" height="28" />
      </a>
      <a class="mx-2" href="https://linkedin.com/in/khanhnguyen2402/">
        <LinkedIn width="28" height="28" />
      </a>
    </div>
  </div>
</div>
