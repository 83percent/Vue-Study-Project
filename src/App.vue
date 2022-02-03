<template>
  <div>
    <keep-component />
  </div>
</template>

<script>
import KeepComponent from "./components/comp/KeepComp.vue";

export default {
  name: "app",
  components: {
    KeepComponent
  }
}
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
* {
    padding: 0;
    margin: 0;
}
ul, ol {
    list-style: none;
}
</style>
