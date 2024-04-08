<script>
  export let homeLink;
</script>

<a href={homeLink} class="h-full block py-4 lg:py-7">
  <h1 id="logo" class="z-50 h-full relative flex items-center">
    <div class="aspect-square invert dark:invert-0 flex">
      <img src="/assets/logo.png" class="object-contain w-10 h-10" alt="Logo" />
    </div>
    <div class="lg:block h-full -mt-2 ml-2.5 pl-2.5 text-black dark:text-white">
      <div class="relative text-[2rem] font-bold">
        Cloud<span class="title__logo">SEN12</span>
      </div>
    </div>
    <span class="sr-only">CloudSEN12 </span>
  </h1>
</a>

<style>
  .title__logo {
    animation: changeColor 3s linear infinite; 
  }

  @keyframes changeColor {
    0% {
      color: #1ca5e0cc;
    }
    33.33% {
      color: #97e373cc; /* Segundo color */
    }
    66.66% {
      color: #79f73fcc; /* Tercer color */
    }
    100% {
      color: #1ca5e0cc; /* Vuelve al primer color */
    }
  }
</style>
