<template>
  <div id="nav">
    <router-link to="/">
      <img src="logo" :alt="alt" id="logo" />
    </router-link>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/pedidos">Pedidos</router-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  props: ["logo", "alt"],
};
</script>

<style scoped>
</style>