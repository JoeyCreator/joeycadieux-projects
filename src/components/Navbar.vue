<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/projects">Projects</router-link>
    <router-link to="/myclient">Myclient</router-link>
  </nav>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
nav a {
  font-weight: 700;
  margin: 10px 20px;
}
</style>