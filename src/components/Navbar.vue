<template>
  <nav class="navbar navbar-expand-lg main-nav">
    <a class="navbar-brand" href="#">
      <img src="https://www.exodus.io/img/exodus-logo.png" alt="Exodus">
    </a>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#">DESIGN</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">JOBS</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">BLOG</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">SUPPORT</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">STATUS</a>
        </li>
      </ul>
    </div>
    <button class="download">DOWNLOAD</button>
  </nav>
</template>

<script>
export default {
  
}
</script>

<style lang="scss">
  nav {
    color: #fff;
    background-color: rgba(35, 38, 48, 0.99);
    font-size: 14px;

    a {
      color: #fff;
      transition: color 0.3s;

      &:hover {
        color: orange;
      }
    }

    .navbar-brand {
      margin-right: 65px;
    }

    .navbar-brand:hover {
      color: #fff;
    }

    .download {
      font-size: 14px;
      padding: 5px 40px;
      color: #fff;
      border: 2px solid #fff;
      border-radius: 50px;
      background-color: rgba(0, 0, 0, 0);

      &:hover {
        border: 2px solid orange;
        color: orange;
      }

      &:focus {
        outline: none;
      }
    }
  }

  .main-nav {
    padding: 25px 35px;
  }
</style>
