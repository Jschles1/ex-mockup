<template>
  <div class="container">
    <div class="row">
      <div class="col-md-5 problems-col">
        <h4>The Problem With Blockchain Assets</h4>
        <p>Blockchain assets (also called digital currency or cryptocurrency) are a young, fragmented new frontier. New people buy bitcoin and miss out on exciting, new opportunities. Diversifying means learning about keys, seeds, wallets, blockchains, mining fees, cold storage, and more.</p>
        <p>Not only do you give up control of your identity, privacy and money; everything quickly turns overwhelming with too much to learn.</p>
        <p><strong>Exodus was created to shift power back to you to control your assets - with no banks, no brokers or institutional oversight.</strong></p>
      </div>

      <div class="macbook">

      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .problems {
    background-color: white;
    padding: 95px 0 120px;
    position: relative;
    overflow: hidden;

    .macbook {
      position: absolute;
      width: 916px;
      height: 540px;
      background: url(https://www.exodus.io/img/macbook-pro-all.jpg) no-repeat center center;
      background-size: contain;
      // top: 114px;
      top: 45px;
      z-index: 4;
      left: 50%;
    }

    .problems-col {

      p {
        font-size: 15px;
        font-weight: 300;
        margin: 40px 0;
        color: rgb(35, 38, 48);
      }

    }
  }
</style>


