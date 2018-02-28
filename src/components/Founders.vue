<template>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <h1>Crafted with <span><i class="fas fa-heart"></i></span> by JP and Daniel.</h1>
        <p>Exodus began development in 2015 from two guys with a passion for blockchain assets.</p>
      </div>
    </div>
    <div class="row">
      <div class="col-md-6">
        <img src="https://www.exodus.io/img/profiles/jp-profile-square.jpg" alt="JP">
        <h3>JP Richardson</h3>
        <h5>Chief Technical Officer</h5>
        <p>Coding the technical magic behind the scenes, JP has published <a href="https://www.npmjs.com/~jprichardson">over 200 open source libraries</a> and has written code in use by most Bitcoin and cryptocurrency software on the web.</p>
      </div>
      <div class="col-md-6">
        <img src="https://www.exodus.io/img/profiles/dc-profile-square.jpg" alt="Daniel">
        <h3>Daniel Castagnoli</h3>
        <h5>Chief Creative Officer</h5>
        <p>From subtle sounds to smooth animations Daniel creates a trusted, warm feeling when using Exodus. He is a master of emotional design and has designed experiences for Apple, BMW, Disney, Louis Vuitton and Nike.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .founders {
    text-align: center;
    color: #fff;
    background: #333844 url(https://www.exodus.io/img/code-bg.jpg) no-repeat center center;
    background-size: cover;
    padding: 75px;
    // font-size: 14px;

    .fa-heart {
      color: #ff415c;
    }

    p {
      font-size: 15px;
      color: rgb(184, 184, 184);
    }

    h5 {
      margin-bottom: 15px;
      color: rgb(184, 184, 184);
    }

    a {
      color: orange;
      text-decoration: none;

      &:hover {
        color: darken(orange, 7.5%);
      }
    }

    img {
      margin: 40px 0 25px;
      height: 170px;
      width: 170px;
      border-radius: 100px;
      border: 2px solid rgb(184, 184, 184);
    }
  }
</style>