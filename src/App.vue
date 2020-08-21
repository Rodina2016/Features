<template>
  <div id="app">
    <app-svg-sprite></app-svg-sprite>
    <app-header></app-header>
    <app-content></app-content>
    <app-footer></app-footer>
  </div>
</template>

<script>
import SvgSprite from './components/SvgSprite.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import Content from './components/Content.vue'
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
    components: {
        AppSvgSprite: SvgSprite,
        AppHeader: Header,
        AppFooter: Footer,
        AppContent: Content
    }
}
</script>

<style lang="scss">
  @import "./assets/styles/variables";
  @import "./assets/styles/layout";
  @import "./assets/styles/common";
  @import "./assets/styles/components/main";
  @import "./assets/styles/components/button";
  @import "./assets/styles/components/header";
  @import "./assets/styles/components/footer";
  @import "./assets/styles/components/menu";
  @import "./assets/styles/components/logo";
  @import "./assets/styles/components/slider";
  @import "./assets/styles/components/search";
</style>
