<template>
  <header class="header">
    <h1>Vue Project</h1>
    <div id="nav">
      <router-link to="/home">Home</router-link> |
      <router-link to="/news">News</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
  #nav {
    padding-top: 15px;
  }

  .header {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 15px;
    margin-bottom: 35px;
  }

  .header a {
    color: #fff;
    padding-right: 5px;
    text-decoration: none;
  }
</style>
