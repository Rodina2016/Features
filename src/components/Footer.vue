<template>
  <footer id="footer" class="footer">
    <div class="wrapper">
      <div class="grid ungutter">
        <div class="xl-4 lg-2 md-3 sm-11 middle-xl grid ungutter">
          <app-logo icon="logo-white"></app-logo>
        </div>
        <div class="footer__menu xl-6 lg-8 md-4 sm-11">
          <div class="footer__menu-item">
            <a href="#" class="footer__menu-link">
              About Us
            </a>
          </div>
          <div class="footer__menu-item">
            <a href="#" class="footer__menu-link">
              Privacy Policy
            </a>
          </div>
        </div>
        <app-search></app-search>
      </div>
    </div>
  </footer>
</template>

<script>
    import Logo from "./Logo";
    import Search from "./Search";

    export default {
        name: 'footer',
        data () {
            return {
                msg: 'footer'
            }
        },
        components: {
            AppLogo: Logo,
            AppSearch: Search,
        }

    }
</script>
