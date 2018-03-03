<template>
  <div class="container">
    <div class="row">
      <div class="col-md-5 col-md-offset-7 features-col">
        <h4>We Made Crypto Beautiful</h4>
        <p>Exodus wraps solid engineering inside beautiful design. We poured our hearts into every detail, from pixel-perfect icons to subtle sounds, making a blockchain asset experience that "just works for normal people". Our goal: Remove the geek requirement to use cryptocurrency and make design a priority - we think it shows.</p>
        <ul class="feature-list">
          <li>
            <div class="feature-icon">
              <span><i class="fas fa-exchange-alt"></i></span>
            </div>
            <div class="feature-content">
              <h6>FRIENDLY, ONE-CLICK EXCHANGE</h6>
              <p>Exodus is designed for people who have never used an exchange. Ready to exchange Bitcoin for Ethereum? Exodus hides the complex details; in seconds, assets are exchanged behind the scenes</p>
              <br>
              <h6><a href="https://vimeo.com/exodusio">Watch Our Help Videos</a></h6>
            </div>
          </li>

          <li>
            <div class="feature-icon">
              <span><i class="far fa-heart"></i></span>
            </div>
            <div class="feature-content">
              <h6>LOVE YOUR BLOCKCHAIN ASSETS</h6>
              <p>Exodus makes it fun and easy to learn and use blockchain assets. No technical talk. No messy wallets. No confusing steps.</p>
              <br>
              <h6><a href="https://medium.com/exodus-movement">Learn More On Our Blog</a></h6>
            </div>
          </li>

          <li>
            <div class="feature-icon">
              <i class="far fa-envelope"></i>
            </div>
            <div class="feature-content">
              <h6>CONTACT US FOR HELP</h6>
              <p>We know problems are frustrating. Exodus provides an online help desk and 24/7 support resources to get problems resolved quickly.</p>
              <br>
              <h6><a href="https://support.exodus.io/">Visit Our 24/7 Help Desk</a></h6>
            </div>
          </li>
        </ul>
      </div>

      <div class="exodus-icons">

      </div>

      
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .features {
    background-color: rgb(245, 245, 245);
    padding: 45px 0;
    position: relative;
    overflow: hidden;

    h6 {
      a {
        text-decoration: none;
        font-weight: 700;
        color: orange;

        &:active,
        &:hover {
          color: darken(orange, 7.5%);
        }
      }
    }

    .exodus-icons {
      width: 900px;
      height: 1360px;

      background: url(https://www.exodus.io/img/exodus-icon-set.png) no-repeat center center;
      z-index: 1;
      background-size: contain;
      position: absolute;
      bottom: -400px;
      right: 50%;

      
      z-index: 1;
    }

    .features-col {
      margin-left: 58.33333333%;

      p {
        font-size: 15px;
        font-weight: 300;
        color: rgb(35, 38, 48);
      }

      ul {
        margin: 60px 0;
        
        li {
          padding: 20px 0;
          list-style: none;
          border-bottom: 1px solid rgb(221, 221, 221);

          &:last-child {
            border: 0;
          }

          .feature-content {
            display: inline-block;
            width: 80%;
          }

          .feature-icon {
            display: inline-block;
            width: 40px;
            vertical-align: top;
            margin-right: 20px;
            color: orange;
            font-size: 30px;
          }
         
          
        }
      }
    }
  }
</style>

