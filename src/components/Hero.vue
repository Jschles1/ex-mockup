<template>
  <div class="row hero-row">
    <div class="col-md-12">
      <h1>Control <span>Your</span> Future Wealth</h1>
      <h5>All-in-one app to secure, manage and exchange blockchain assets.</h5>
      <div class="hero-buttons">
        <button class="hero-button">WATCH NEW LAUNCH VIDEO</button>
        <button class="hero-button">WATCH EXODUS DEMO VIDEO</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .hero-row {
    padding: 100px;

    h1 {
      margin: 50px 0 40px;
      font-size: 65px;

      span {
        font-size: 35px;
        color: gray;
      }
    }

    .hero-buttons {
      margin-top: 120px;

      .hero-button {
        font-size: 14px;
        margin: 0 10px;
        padding: 15px 35px;
        color: #fff;
        border: 0;
        border-radius: 50px;
        background-color: orange;
        transition: background-color 0.5s;

        &:hover {
          cursor: pointer;
          background-color: darken(orange, 7.5%);
        }

        &:active,
        &:visited,
        &:focus {
          border: none;
          outline: none;
        }
      }
    }
  }
</style>
