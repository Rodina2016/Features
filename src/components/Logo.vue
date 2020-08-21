<template>
  <div class="logo">
  <a href="/" class="logo__link">
    <svg class="logo__svg">
      <use v-bind:href="'#'+icon"></use>
    </svg>
  </a>
  </div>
</template>

<script>
    export default {
        name: 'logo',
        props: ['icon'],
       }
</script>
