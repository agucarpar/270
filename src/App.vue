<template>
  <div id="app">
    <RightText class="right-text" />
    <LeftText class="left-text" />
  </div>
</template>

<script>
import RightText from '@/components/RightText.vue'
import LeftText from '@/components/LeftText.vue'
export default {
  name: 'App',
  components: {
    RightText,
    LeftText
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}


</style>

