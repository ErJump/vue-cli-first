<template>
  <div class="hero">
    <div class="container">
      <div class="row">
        <div class="col-12 hero">
          <h1>IS THAT THE REAL VUE?</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroMain',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .hero {
    background-image: url(https://www.icegif.com/wp-content/uploads/2022/03/icegif-1061.gif);
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