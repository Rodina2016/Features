<template>
  <header id="header" class="header">
    <div class="wrapper">
      <div class="grid">
        <div class="middle-xl grid ungutter xl-3 md-6 cell">
          <app-logo icon="logo"></app-logo>
        </div>
        <app-menu></app-menu>
      </div>
    </div>
  </header>
</template>

<script>
    import Logo from "./Logo";
    import Menu from "./Menu";

    export default {
        name: 'header',
        data () {
            return {
                msg: 'Header'
            }
        },
        components: {
            AppLogo: Logo,
            AppMenu: Menu
        }
    }
</script>
