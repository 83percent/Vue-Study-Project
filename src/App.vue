<template>
  <div>
    <MenuVue />
    <div id="wrap">
      <router-view></router-view>
    </div>
  </div>

</template>

<script>
import MenuVue from './components/nav/menu.vue';
export default {
  name: "app",
  components: {
    MenuVue
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
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
ul, ol {
    list-style: none;
}

#wrap {
  display: flex;
  justify-content: center;
  min-height: 100vh;
  min-width: 100vw;

}

</style>
