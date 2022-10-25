<script>
export default {
  name: "FooterComponent",
};
</script>

<template>
  <footer>
    <section class="footer-content">
      <div class="box-content">
        <img width="100px" src="../assets/images/image-retro-pcs.jpg" alt="" />
        <div class="content">
          <h1>01</h1>
          <p class="sub-title">Lorem ipsum dolor</p>
          <p>Duis sed arcu non neque feugiat cursus.</p>
        </div>
      </div>
      <div class="box-content">
        <img
          width="100px"
          src="../assets/images/image-top-laptops.jpg"
          alt=""
        />
        <div class="content">
          <h1>02</h1>
          <p class="sub-title">Lorem ipsum dolor</p>
          <p>Duis sed arcu non neque feugiat cursus.</p>
        </div>
      </div>
      <div class="box-content final">
        <img
          width="100px"
          src="../assets/images/image-gaming-growth.jpg"
          alt=""
        />
        <div class="content">
          <h1>03</h1>
          <p class="sub-title">Lorem ipsum dolor</p>
          <p>Duis sed arcu non neque feugiat cursus.</p>
        </div>
      </div>
    </section>
  </footer>
</template>

<style lang="scss">
@import "../styles/footerStyle.scss";
</style>
