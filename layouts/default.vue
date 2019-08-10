<template>
  <div class="antialiased">
    <div class="max-w-5xl mx-auto px-6 md:px-8 text-lg sm:text-xl md:text-2xl lg:text-3xl md:font-light text-gray-700 leading-tight">
      <navigation />
      <nuxt/>
    </div>
  </div>
</template>

<script>
  import Navigation from "../components/Navigation";

  export default {
    components: {
      Navigation
    }
  }
</script>