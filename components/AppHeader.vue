<template>
  <div>
<header class="header">
  <h1 class="title">Dad Jokes</h1>
  <ul>
    <li>
      <nuxt-link to="/">Home</nuxt-link>
    </li>
    <li>
      <nuxt-link to="/jokes">Jokes</nuxt-link>
    </li>
    <li>
      <nuxt-link to="/about">About</nuxt-link>
    </li>
  </ul>
</header>
  </div>
</template>

<script>
  export default {
    name:'AppHeader'
  }
</script>

<style scoped>

</style>
