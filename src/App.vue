<script>
import FooterComponent from "./components/FooterComponent.vue";
import HeaderComponentVue from "./components/HeaderComponent.vue";
import SectionComponent from "./components/SectionComponent.vue";

export default {
  data() {
    return {
      menu: false,
    };
  },
  components: {
    FooterComponent,
    HeaderComponentVue,
    SectionComponent,
  },
  methods: {
    mostrarMenu() {
      this.menu = !this.menu;
    },
  },
};
</script>

<template>
  <main>
    <HeaderComponentVue v-on:menu="mostrarMenu" />
    <SectionComponent />
    <FooterComponent />
  </main>

  <div v-if="menu" class="menu">
    <img
      src="./assets/images/icon-menu-close.svg"
      alt=""
      @click="mostrarMenu"
    />
    <ul v-if="menu">
      <li>Home</li>
      <li>New</li>
      <li>Popular</li>
      <li>Trending</li>
      <li>Categories</li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
@import "./styles/appStyle.scss";
</style>
