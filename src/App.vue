<template>
  <div id="app">
    <MyTitle />
  </div>
</template>

<script>
import MyTitle from "./components/MyTitle.vue";
export default {
  name: 'App',
  components: {
    MyTitle,
},
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
