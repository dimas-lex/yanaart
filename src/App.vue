<template>
  <div id="app">
    <AsyncComponent />
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    AsyncComponent: () => import('./AsyncComponent.vue'),
  },
};
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    background-color: #213443;
    color: #2c3e50;
    margin-top: 0px;
    padding: 0;
    width: 100vw;
    height: 100vh;
  }
</style>
