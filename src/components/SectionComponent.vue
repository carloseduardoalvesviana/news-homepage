<script>
export default {
  name: "SectionComponent",
};
</script>

<template>
  <section>
    <div class="contentOne">
      <img src="../assets/images/image-web-3-desktop.jpg" alt="" />
      <section class="sectionOne">
        <div class="heading">
          <h1>The Bright Future of Web 3.0</h1>
        </div>

        <div class="sectionContent">
          <p class="text-content">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis sed
            arcu non neque feugiat cursus. Lorem ipsum dolor sit amet, arcu non
            neque feugiat cursus.
          </p>
          <button class="button-action">READE MORE</button>
        </div>
      </section>
    </div>

    <div class="contentTwo">
      <h1 class="title-action">New</h1>
      <section class="content">
        <ul>
          <li>
            <div class="content-text">
              <h1>Lorem Ipsum</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
          </li>

          <li>
            <div class="content-text">
              <h1>Lorem Ipsum</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
          </li>

          <li>
            <div class="content-text">
              <h1>Lorem Ipsum</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
            </div>
          </li>
        </ul>
      </section>
    </div>
  </section>
</template>

<style lang="scss" scoped>
@import "../styles/sectionStyle.scss";
</style>
