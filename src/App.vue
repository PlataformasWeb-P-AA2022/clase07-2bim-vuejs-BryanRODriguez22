<template>
  <div id="app">
    <TaskItems />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TaskItems from './components/taskItems.vue'
export default {
  name: 'App',
  components: {
    TaskItems,
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
</style>