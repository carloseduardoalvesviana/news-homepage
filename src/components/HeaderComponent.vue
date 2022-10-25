<script>
export default {
  name: "HeaderComponent",
};
</script>

<template>
  <nav>
    <img src="../assets/images/logo.svg" alt="" srcset="" />

    <ul>
      <li>Home</li>
      <li>New</li>
      <li>Popular</li>
      <li>Trending</li>
      <li>Categories</li>

      <li class="icone" @click="this.$emit('menu')">
        <img src="../assets/images/icon-menu.svg" alt="" />
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
@import "../styles/headerStyle.scss";
</style>
