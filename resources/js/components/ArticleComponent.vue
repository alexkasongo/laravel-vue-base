<template>
  <div class="article page USD">
    <h1 class="article__h1">H1 h1</h1>
    <h2 class="article__h2">H2 h2</h2>
    <h3 class="article__h3">H3 h3</h3>
    <h4 class="article__h4">H4 h4</h4>
    <h5 class="article__h5">H5 h5</h5>
    <h6 class="article__h6">H6 h6</h6>
    <div class="article__para">
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facilis
      minus sint voluptatem assumenda quae fugit aspernatur sunt
      distinctio corrupti maxime veritatis, rem, aliquid obcaecati
      reprehenderit nemo, atque optio quos tempore.
    </div>
    <div class="article__caption">atque optio quos tempore.</div>
    <a href="#">Link</a>
    <!-- <div class="article__box-shadow"></div>
    <span class="price">45</span>-->
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Article Component mounted.");
  },
};
</script>

<style lang="scss" scoped>
@import "../../sass/7-components/_article.scss";
</style>
