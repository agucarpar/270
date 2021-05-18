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
@import '../styles/_keyframes.scss';
  .right-text-wrapper{
    display: flex;
    writing-mode: tb-rl;
    justify-content: space-evenly;
    height: 100%;
    float: right;
    animation-name: verticalMovement;
    animation-duration: 3s;

    
  }
</style>


