<template>
  <div class="container">
    <div class="row">
      <div class="download-now">
        <h4>Exodus is available for Windows, Mac and Linux.</h4>
        <button class="download-button">DOWNLOAD</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  .download {
    text-align: center;
    padding: 120px 0 100px;

    .download-now {
      margin: 0 auto;

      .download-button {
        font-size: 14px;
        margin: 10px 0;
        padding: 12px 140px;
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

