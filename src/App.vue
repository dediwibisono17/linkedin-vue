<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Card>
    </Card>
    <Analytic />
    <resource />
    <experience />
    <!-- <Button msg="lala" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
// import Button from "./components/UI/Button.vue";
import Card from "./components/UI/Card.vue";
import Analytic from "./components/UI/Analytic.vue";
import Resource from "./components/UI/Resources.vue";
import Experience from "./components/UI/Experience.vue"

export default {
  name: "App",
  components: {
    // HelloWorld,
    // Button,
    Card,
    Analytic,
    Resource,
    Experience
  }
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // background: #ececec;
  margin-top: 60px;
}
</style>
