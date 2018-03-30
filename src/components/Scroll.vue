<template>
  <div class="container">
    <div class="row">
      <div class="scroll-button">
        <i class="fas fa-angle-up"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .scroll {
    background-color: #495061;
    height: 65px;
    width: 100%;
    position: relative;

    &-button {
      color: #fff;
      background-color: rgba(0, 0, 0, 0.15);
      position: absolute;
      top: 0;
      right: 50px;
      vertical-align: middle;
      font-size: 25px;
      line-height: 65px;
      text-align: center;
      height: 65px;
      width: 75px;
      z-index: 5;
      transition: background-color .2s;

      &:hover {
        background-color: rgba(0, 0, 0, 0.4);
      }
    }
  }
</style>