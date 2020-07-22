<template>
  <div class="article">
    <h1 class="article__title">demo title</h1>
  </div>
</template>

<script>
export default {
  mounted() {
    console.log("Component mounted.");
  },
};
</script>

<style lang="scss" scoped>
@import "../../sass/components/_article.scss";
</style>