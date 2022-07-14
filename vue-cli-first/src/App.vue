<template>
  <div id="app">
    <HeroMain/>
    <HeroSub/>
  </div>
</template>

<script>
import HeroMain from './components/HeroMain.vue'
import HeroSub from './components/HeroSub.vue'

export default {
  name: 'App',
  components: {
    HeroMain,
    HeroSub
  }
}
</script>

<style lang="scss">
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
.hero {
    background-image: url();
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    height: 70vh;
  }
  .hero>*{
    color: #fff;
    font-size: 50px;
    text-shadow: 3px 3px #000;
    transform: translateY(20px);
  }
</style>
