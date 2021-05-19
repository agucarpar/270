<template>
  <div id="app">
    <aside>
      <LeftText />
    </aside>
    <div class="central-section">
      <section>
        <Logo />
      </section>
      <article class="claim-wrapper">
        <Claim />
      </article>
    </div>
    <aside>
      <RightText />
    </aside>
  </div>
</template>

<script>
import RightText from '@/components/RightText.vue'
import LeftText from '@/components/LeftText.vue'
import Claim from '@/components/Claim.vue'
import Logo from '@/components/Logo.vue'
export default {
  name: 'App',
  components: {
    RightText,
    LeftText,
    Claim,
    Logo
  }
}
</script>

<style lang="scss" scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    .central-section {
      .claim-wrapper {
        display: flex;
        justify-content: center
      }
    }
}


</style>

