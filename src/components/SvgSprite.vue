<template>
  <svg id="SvgSprite" style="visibility: hidden; display: none">
    <symbol width="49" height="35" viewBox="0 0 49 35" fill="none" id="logo">
      <rect y="15" width="20" height="20" rx="10" fill="#9C69E2"/>
      <rect x="29" width="20" height="35" rx="10" fill="#F063B8"/>
    </symbol>
    <symbol width="49" height="35" viewBox="0 0 49 35" fill="none" id="logo-white">
      <rect y="15" width="20" height="20" rx="10" fill="white"/>
      <rect x="29" width="20" height="35" rx="10" fill="white"/>
    </symbol>
    <symbol width="10" height="6" viewBox="0 0 10 6" id="up">
      <path fill-rule="evenodd" clip-rule="evenodd" d="M5.70633 2.79356C5.31582 3.18404 4.6827 3.18404 4.29219 2.79356L1.87467 0.376274C1.52957 0.0312008 0.970075 0.0312017 0.62497 0.376275C0.279818 0.721394 0.279818 1.28098 0.62497 1.6261L4.37443 5.37521C4.71954 5.72028 5.27903 5.72028 5.62414 5.37521L6.24909 4.75031C6.2491 4.7503 6.2491 4.75029 6.24909 4.75028C6.24909 4.75028 6.24909 4.75026 6.24909 4.75026L9.37503 1.62461C9.72018 1.2795 9.72018 0.719912 9.37503 0.374793C9.02992 0.0297193 8.47043 0.0297198 8.12533 0.374793L5.70633 2.79356Z"/>
    </symbol>
    <symbol width="22" height="16" viewBox="0 0 22 16" fill="none" id="arrow-right">
      <path d="M15 15L21 8L15 1" stroke="#9C69E2" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      <path d="M21 8H1" stroke="#9C69E2" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    </symbol>
    <symbol width="36" height="24" viewBox="0 0 36 24" id="burger">
      <rect width="36" height="3" rx="1.5" fill="#212353"/>
      <rect y="10.5" width="36" height="3" rx="1.5" fill="#212353"/>
      <rect y="21" width="36" height="3" rx="1.5" fill="#212353"/>
    </symbol>
    <symbol width="28" height="28" viewBox="0 0 28 28" id="burger-active">
      <rect y="25.4558" width="36" height="3" rx="1.5" transform="rotate(-45 0 25.4558)" fill="#212353"/>
      <rect width="36" height="3" rx="1.5" transform="matrix(-0.707107 -0.707107 -0.707107 0.707107 27.5772 25.4558)" fill="#212353"/>
    </symbol>
    <symbol width="11" height="18" viewBox="0 0 11 18" fill="none" id="up-big">
      <path fill-rule="evenodd" clip-rule="evenodd" d="M5.91751 8.30225C6.29746 8.69087 6.29746 9.3118 5.91751 9.70042L0.686091 15.0512C0.306144 15.4399 0.306145 16.0608 0.686092 16.4494L1.48705 17.2686C1.87932 17.6699 2.52486 17.6699 2.91713 17.2686L10.3165 9.70037C10.6965 9.31175 10.6965 8.69082 10.3165 8.3022L8.80055 6.75163C8.80053 6.75162 8.80051 6.75162 8.8005 6.75163C8.80049 6.75164 8.80046 6.75164 8.80045 6.75163L2.91452 0.73136C2.52225 0.330138 1.87671 0.330139 1.48444 0.73136L0.683481 1.5506C0.303535 1.93922 0.303535 2.56015 0.683482 2.94876L5.91751 8.30225Z" fill="#212353"/>
    </symbol>

  </svg>
</template>

<script>
    export default {
        name: 'SvgSprite',
    }
</script>
