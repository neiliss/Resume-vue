<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld
    msg="| NEIL ISSEROW | CALIFORNIA, USA | NEIL@ISSEROW.COM | 415-515-0222 |"
  />
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
