<template>
    <div id="jumbo">
        <img src="../assets/Mario.jpg" alt="Super Mario">
        <div id="jumbo-text"> That's SuperMarioJumbo!</div>
    </div>
</template>

<script>
export default {
    name:'MyHero',
};
</script>

<style scoped>
  #jumbo{
    height: 200px;
    background-color: lightseagreen;
    display: flex;
    line-height: 200px;
    color:white;
    font-weight: 800;
    font-size: 2rem;
    margin: 0 50px;
    border: 1px solid black;
  };
  
</style>