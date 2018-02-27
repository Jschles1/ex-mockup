<template>
  <div class="container">
    <div class="row">
      <div class="col-md-4">
        <div class="benefit-icon">
          <span><i class="fas fa-key"></i></span>
        </div>
        <div class="benefit-content">
          <h6>CONTROL YOUR KEYS</h6>
          <p>Exodus encrypts private keys and transaction data locally for your eyes only. Your data remains private - no account setup required.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="benefit-icon">
          <span><i class="fas fa-chart-pie"></i></span>
        </div>
        <div class="benefit-content">
          <h6>BEAUTIFUL LIVE CHARTS</h6>
          <p>Track the value of your blockchain asset portfolio, in real time, as market conditions change.</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="benefit-icon">
          <span><i class="fas fa-paint-brush"></i></span>
        </div>
        <div class="benefit-content">
          <h6>PERSONALIZED FOR YOU</h6>
          <p>Like darker themes? How about a subtle space background? Exodus gives you a personal look with everything from traditional gray to patterns or customized themes.</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .benefits {
    background-color: #fff;
    padding: 100px;
    font-size: 14px;

    .benefit-icon {
      display: inline-block;
      width: 40px;
      vertical-align: top;
      margin-right: 20px;
      color: orange;

      font-size: 30px;
    }

    .benefit-content {
      display: inline-block;
      width: 80%;
    }
  }
</style>