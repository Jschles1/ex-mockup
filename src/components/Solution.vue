<template>
  <div class="container">
    <div class="row solution-hero">
      <h1>Exodus gives blockchain asset investors a platform to secure, exchange and manage wealth inside one beautiful application.</h1>
      <p>Exodus currently supports Bitcoin, Bitcoin Cash, Bitcoin Gold, Dash, Decred, Ethereum, Ethereum Classic, Litecoin, Vertcoin plus more Ethereum powered asset tokens including 0x, Aragon, Augur, Basic Attention Token (BAT), Bancor, Civic, District0x, EOS, Edgeless, FirstBlood, FunFair, Gnosis, Golem, iExec RLC, Matchpool, Metal, Numeraire, OmiseGo, SALT, SingularDTV, Storj, Status, WeTrust and Wings.</p>
    </div>

    <div class="coins">

    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .solution {
    margin-top: 120px;
    background: #333844 url(https://www.exodus.io/img/polygonal-bg.jpg) no-repeat center center;
    padding: 120px 0 190px;
    // padding-bottom: 190px;
    position: relative;
    text-align: center;
    color: white;

    p {
      margin-top: 20px;
      font-size: 15px;
      color: rgb(192, 192, 192);
    }

    .coins {
      width: 1600px;
      height: 130px;
      position: absolute;
      bottom: -66px;
      left: 50%;
      -webkit-transform: translateX(-50%);
      transform: translateX(-50%);
      background: url(https://www.exodus.io/img/asset-list-12-28-2017@2x.png) no-repeat center center;
      background-size: contain;
    }  
  }
</style>
