<template>
  <div>
    <h1>{{ titre }}</h1>
    <p>{{ contenu }}</p>
  </div>
</template>

<script>
export default {
  name: 'Article',
  props: ['titre', 'contenu']
}

</script>
<style>

</style>
