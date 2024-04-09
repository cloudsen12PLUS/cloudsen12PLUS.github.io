<script>
  export let homeLink;
</script>

<a href={homeLink} class="h-full block py-4 lg:py-7">
  <h1 id="logo" class="z-50 h-full relative flex items-center">
    <div class="aspect-square flex">
      <img src="/assets/logo.png" class="object-contain w-10 h-10" alt="Logo" />
    </div>
    <div class="lg:block h-full pl-2.5 text-black dark:text-white">
      <div class="relative lg:text-3xl font-bold title__h">
        Cloud<span class="text-with-color-style">SEN12</span>
      </div>
    </div>    
    <span class="sr-only">CloudSEN12 </span>
  </h1>
</a>


<!-- Make the SEN12 change according to the button style -->
<style>
  @media(max-width:768px){
    .title__h{
      font-size: 1.5rem;
    }
  }
  [data-style="Primary"] {
    @apply bg-[rgba(var(--primaryColor),0.8)] hover:bg-[rgba(var(--primaryColor),1)];
  }
  .text-with-color-style {
    @apply text-[rgba(var(--primaryColor),0.8)];
  }
</style>

