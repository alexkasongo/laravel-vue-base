<template>
  <div class="playground page USD">
    <div class="playground__box-1 playground__box">
      <div class="playground__heading">Typography</div>
      <div class="playground__typography">
        <h1 class="playground__h1">H1 h1</h1>
        <h2 class="playground__h2">H2 h2</h2>
        <h3 class="playground__h3">H3 h3</h3>
        <h4 class="playground__h4">H4 h4</h4>
        <h5 class="playground__h5">H5 h5</h5>
        <h6 class="playground__h6">H6 h6</h6>
        <div class="playground__para">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facilis
          minus sint voluptatem assumenda quae fugit aspernatur sunt
          distinctio corrupti maxime veritatis, rem, aliquid obcaecati
          reprehenderit nemo, atque optio quos tempore.
        </div>
      </div>
    </div>

    <div class="playground__box-2 playground__box">
      <div class="playground__heading">Captions</div>
      <div class="playground__caption">atque optio quos tempore.</div>
    </div>

    <div class="playground__box-3 playground__box">
      <div class="playground__heading">Links</div>
      <a class="playground__link" href="#">Link</a>
    </div>

    <div class="playground__box-4 playground__box">
      <div class="playground__heading">Box Shadow</div>
      <div class="playground__box-s playground__boxhadow"></div>
    </div>

    <div class="playground__box-5 playground__box">
      <div class="playground__heading">Lists</div>
      <ul class="playground__ul">
        <li>
          <a href="#" class="playground__a">List 1</a>
        </li>
        <li>
          <a href="#" class="playground__a">List 2</a>
        </li>
        <li>
          <a href="#" class="playground__a">List 3</a>
        </li>
        <li>
          <a href="#" class="playground__a">List 4</a>
        </li>
      </ul>
    </div>

    <div class="playground__box-6 playground__box">
      <div class="playground__heading">Inputs + Buttons</div>
      <input type="text" placeholder="placeholder text" />
      <button class="playground__btn">Click</button>
      <button class="playground__btn-shadow">Click</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "playground-component",
  mounted() {
    console.log("Playground Component mounted.");
  },
};
</script>
