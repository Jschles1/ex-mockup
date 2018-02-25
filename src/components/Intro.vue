<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-12 text-center">
        <h3>Exodus is the first desktop multi-asset wallet with ShapeShift built in.</h3>
      </div>
    </div>

    <div class="row">
      <div class="col-md-4">
        <article class="post">
          <figure>
            <a href="#">
              <img src="https://www.exodus.io/img/exodus-portfolio-2017-08-thum@2x.jpg" alt="Exodus Porfolio">
            </a>
          </figure>
          <figcaption>
            <h6>PORTFOLIO</h6>
            <p>Live charts turn your diversified portfolio into a bottom line.</p>
          </figcaption>
        </article>
      </div>
      <div class="col-md-4">
        <article class="post">
          <figure>
            <a href="#">
              <img src="https://www.exodus.io/img/exodus-exchange-aurora-ss-thum@2x.jpg" alt="Exodus Exchange">
            </a>
          </figure>
          <figcaption>
            <h6>EXCHANGE</h6>
            <p>A seamless, one click, ShapeShift experience.</p>
          </figcaption>
        </article>
      </div>
      <div class="col-md-4">
        <article class="post">
          <figure>
            <a href="#">
              <img src="https://www.exodus.io/img/exodus-wallet-btc-thum@2x.jpg" alt="Exodus Wallet">
            </a>
          </figure>
          <figcaption>
            <h6>MULTI-ASSET WALLET</h6>
            <p>Bitcoin, Ethereum, Litecoin, Dash, EOS and more.</p>
          </figcaption>
        </article>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .intro {
    background-color: rgb(245, 245, 245);
    padding: 30px;

    h3 {
      padding: 30px;
      font-weight: 700;
      color: orange;
    }

    h6 {
      color: orange;

      &:hover {
        color: darken(orange, 7.5%);
      }
    }

    img {
      width: 100%;
      height: auto;
    }

    figcaption {
      margin: 30px;
      text-align: center;
    }
  }
</style>