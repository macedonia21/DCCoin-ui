<template>
  <div id="app">
    <div class="container"><h2><a class="header-link" href="/">DCCoin wallet</a></h2>
      <router-view :key="$route.fullPath"/></div>
  </div>
</template>

<script>
export default {
  name: 'app',
  created()
  {

  },
}
</script>

<style>
.header-link {
  color: black;
  text-decoration: none; /* no underline */
}

.break-word {
  word-wrap: break-word;
}
</style>
