<template>
  <div id="app">
    <Menu />
   
  </div>
</template>
<script>
import Menu from "@/components/Menu.vue";

export default {
  components: {
    Menu,
    
  },
};
</script>

<style scoped>
#app {
  box-sizing: border-box;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}

</style>
