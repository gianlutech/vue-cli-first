<template>
  <div id="app">
    <Title />
    <img alt="Vue logo" src="./assets/logo.png" />
    <h1>Hello World!</h1>
  </div>
</template>

<script>
import Title from "./components/Title.vue";

export default {
  name: "App",
  components: {
    Title: Title,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;

  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
