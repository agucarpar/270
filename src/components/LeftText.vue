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
  .left-text-wrapper{
    display: flex;
    writing-mode: tb-rl;
    justify-content: space-evenly;
    height: 100%;
    
    animation-duration: 3s;
    animation-name: verticalMovement2;
    
    
    .main {
      word-spacing: 2rem;
      transform: rotate(
          180deg   
        );
    };

    @keyframes verticalMovement2 {
      0% {
        transform: translateY(-100%);
      }
      100% {
        transform: translateX(0);
      }
    }

  }
</style>


