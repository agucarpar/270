<template>
  <div class="claim-wrapper">
    <div class="claim-wrapper__claim">
      <p> A <b>NEW WAY</b> TO LEARN MUSIC.</p>
    </div>
    <div class="claim-wrapper__blinker">
      <Blinker/>
    </div>
  </div>
</template>

<script>
import Blinker from '@/components/Blinker.vue'
export default {
  name:"Claim",
  components: {
    Blinker
  }
}
</script>

<style lang="scss" scoped>
@import '../styles/variables.scss';
  .claim-wrapper {
    position: relative;
    top: 5rem;
    display: flex;
    flex-direction:column ;
    &__claim {
      color: $colorLandingText;
      border: 10px solid $colorLandingText;
      padding: 1rem;
      width: 26rem;
      text-align: center;
    }
    &__blinker {
      animation: blinkerText 1.2s infinite;
    }
  }
</style>