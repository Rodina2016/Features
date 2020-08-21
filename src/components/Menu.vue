<template>
  <nav class="menu grid ungutter middle-xl xl-19 md-22 cell" v-bind:class="{ 'active': !hide}">
    <div class="menu__wrap grid ungutter xl-16 lg-14 md-22" v-bind:class="{ 'hidden-md': hide}">
      <div class="menu__item">
        <a href="#" class="menu__item-link">
          About
        </a>
      </div>
      <div class="menu__item">
        <a href="#" class="menu__item-link">
          Help
          <svg class="menu__item-svg">
            <use v-if="hide" xlink:href="#up"></use>
            <use v-else xlink:href="#up-big"></use>
          </svg>
        </a>
        <div class="menu__item-sub">
          <div class="menu__item-wrap">
            <div class="menu__sub-item">
              <a href="#" class="menu__sub-link">
                User Guide
              </a>
            </div>
            <div class="menu__sub-item">
              <a href="#" class="menu__sub-link">
                Contact Support
              </a>
            </div>
          </div>
        </div>
      </div>
      <div class="menu__item">
        <a href="#" class="menu__item-link">
          Features
        </a>
      </div>
    </div>
    <div class="menu__btn end-xl xl-6 lg-8 md-22 cell center-md" v-bind:class="{ 'hidden-md': hide}">
      <a href="#" class="button button-rounded">
        Sign Up
      </a>
    </div>
    <div class="menu__burger hidden-xl visible-md" v-on:click="hide = !hide" v-bind:class="{ 'active': !hide}">
      <svg class="menu__burger-svg">
        <use v-if="hide" xlink:href="#burger"></use>
        <use v-else xlink:href="#burger-active"></use>
      </svg>
    </div>
</nav>
</template>

<script>
    export default {
        name: 'menu',
        data: function () {
            return {
                hide: true
            }
        },

    }
</script>
