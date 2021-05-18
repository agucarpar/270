<template>
<div class="right-text-wrapper">
  <p>Production</p>
  <p>Composing For Film</p>
  <p>The art of the music</p>
</div>
  
</template>

<script>
export default {
  name: 'RightText',

}
</script>

<style lang="scss">
  .right-text-wrapper{
    display: flex;
    writing-mode: tb-rl;
    justify-content: space-evenly;
    height: 100%;
    float: right;
    animation-name: verticalMovement;
    animation-duration: 3s;

    @keyframes verticalMovement {
      0% {
        transform: translatey(-100%);
      }
      100% {
        transform: translateX(0);
      }
    }
  }
</style>


