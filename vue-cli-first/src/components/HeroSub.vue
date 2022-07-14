<template>
  <div class="hero">
    <div class="container">
      <div class="row">
        <div class="col-12 hero">
          <h1>YES IT IS</h1>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSub',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .hero {
    background-image: url(https://c.tenor.com/5mBHHj2kkQoAAAAC/the-cuphead-show-netflix.gif);
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