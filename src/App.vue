<template>
  <div>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/services">Services</router-link> |
      <router-link to="/contact">Contact</router-link>
    </nav>
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
};
</script>

<style scoped>
nav {
  padding: 1rem;
  background-color: #f0f0f0;
}
nav a {
  margin: 0 0.5rem;
  text-decoration: none;
}
</style>
