<template>
  <div>
    <h1>Welcome to News</h1>
    <div class="buttonContainer">
      <a class="button" v-on:click="printMsg">Click Me!</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'News',
  methods: {
    printMsg() {
      console.log("You are currently on the News page.")
    }
  }
}
</script>

<style scoped>
  a {
    text-decoration: none;
  }

  a.button {
    border-radius: 2em;
    background-color: #4fc08d;
    transition: all 0.15s ease;
    box-sizing: border-box;
    border: 1px solid #4fc08d;
  }

  .button {
    font-size: 1.5em;
    color: #fff;
    margin: 0.2em 0;
    width: 200px;
    text-align: center;
    padding: 12px 24px;
    display: inline-block;
    vertical-align: middle;
  }

  .buttonContainer {
    display: flex;
    padding: 15px;
    align-items: center;
    justify-content: center;
  }
</style>
