<template>
  <div id="app" class="flex f-column min-h-100vh">
    <header-vue />
    <main-vue />
    <footer-vue />
    <button-aside />
  </div>
</template>

<script>
import HeaderVue from "./components/header-vue.vue";
import MainVue from "./components/main-vue.vue";
import FooterVue from "./components/footer-vue.vue";
import ButtonAside from './components/button-aside.vue';

export default {
  name: 'App',

  components: { HeaderVue, MainVue, FooterVue, ButtonAside }
}
</script>