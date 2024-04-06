<script>
  export let homeLink;
</script>

<a href={homeLink} class="h-full block py-4 lg:py-7">
  <h1 id="logo" class="z-50 h-full relative flex">
    <div class="aspect-square invert dark:invert-0 flex">
      <img src="/assets/logo.png" alt="Logo" class="object-contain" />
    </div>
    <div
      class="hidden lg:block h-full ml-2.5 pl-2.5 text-black dark:text-white"
    >
      <div class="relative text-[1.6rem] font-bold">
        Cloud<span class="text-blue-400">SEN12</span>
      </div>
    </div>
    <span class="sr-only">CloudSEN12 </span>
  </h1>
</a>
