<template>
  <div id="app" class="sm-overflow-y">
    <!-- <img src="./assets/logo.png"> -->
    <router-view style="padding-bottom: 53px"/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgba(255, 255, 255, 0.4);
  /* margin-top: 60px; */
}

</style>
