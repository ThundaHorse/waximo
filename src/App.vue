<template>
  <div id="app">
    <div id="header">
      <div class="nav-row">
        <router-link to="/">Home</router-link> |
        <router-link to="/privacy-policy">Privacy Policy</router-link>
      </div>
    </div>

    <router-view />

    <div id="footer">
      <h1>Footer</h1>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'App',
  };
</script>

<style scoped>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
