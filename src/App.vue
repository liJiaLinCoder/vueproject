<template>
  <div id="app">
    <dialogView></dialogView>

  </div>
</template>
<script>
import dialogView from '@/components/view.vue'

export default {

  components:{
    dialogView,
  }
}
</script>

<style>
body{
  margin: 0px;padding: 0px;
}
#app {
  position: relative;
  width: 100vw;height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-size: cover;
  background-image: url("./assets/skin01.png");
}

</style>
