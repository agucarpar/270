<template>
<div class="left-text-wrapper">
  <p class="main">MUSICAL PRODUCTION FOR THE DIGITAL AGE</p>
</div>
  
</template>

<script>
export default {
  name: 'LeftText',

}
</script>

<style lang="scss">
@import '../styles/_keyframes.scss';
  .left-text-wrapper{
    display: flex;
    writing-mode: tb-rl;
    justify-content: space-evenly;
    height: 100%;
    
    animation-duration: 3s;
    animation-name: verticalMovement;
    
    
    .main {
      word-spacing: 2rem;
      transform: rotate(
          180deg   
        );
    };

  }
</style>


