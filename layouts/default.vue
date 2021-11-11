<template>
  <div>
    <div class="flex justify-center items-center space-x-5 h-10">
      <nuxt-link to="/">
        Accueil
      </nuxt-link>
      <nuxt-link to="/about">
        A propos
      </nuxt-link>
      <nuxt-link to="/blog">
        Blog
      </nuxt-link>
    </div>
    <div class="flex flex-col justify-center items-center h-screen bg-gray-200">
      <div class="w-1/2 h-80 bg-white flex flex-col justify-center items-center rounded">
        <nuxt />
      </div>
    </div>
  </div>
</template>
<style module>
  a {
    @apply text-blue-600 uppercase;
  }
  a:hover {
    @apply text-blue-900;
  }
</style>
