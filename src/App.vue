<template>
  <div id="app" class="flex f-column min-h-100vh">
    <div class="relative topWebPage fixed top left right z-full">
      <header-vue />
      <aside-vue />
    </div>
    <main-vue />
    <footer-vue />
    <button-aside />
  </div>
</template>

<script>
import HeaderVue from "./components/header-vue.vue";
import AsideVue from "./components/aside-vue.vue";
import MainVue from "./components/main-vue.vue";
import FooterVue from "./components/footer-vue.vue";
import ButtonAside from "./components/button-aside.vue";

export default {
  name: "App",

  components: { HeaderVue, AsideVue, MainVue, FooterVue, ButtonAside },
};
</script>


<style lang="scss">
h4 {
  padding-bottom: 2rem !important;
  font-size: 2rem;
}

.response {
  margin-top: 1rem;
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}

.collapse {
  border-collapse: collapse;
}

.bg-gray-0 {
  background-color: rgb(184, 196, 182);
}

.topWebPage {
  height: 52px;
}
</style>