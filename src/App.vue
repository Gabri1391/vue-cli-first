<template>
  <div id="app">
    <MyTitle />
    <MyHero />
  </div>
</template>

<script>
import MyTitle from "./components/MyTitle.vue";
import MyHero from "./components/MyHero.vue";
export default {
  name: 'App',
  components: {
    MyTitle,
    MyHero,
},
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
}
</style>
