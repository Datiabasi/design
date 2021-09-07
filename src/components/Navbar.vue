<template>
  <div class="container px-md-5">
    <div class="nav-section pt-4 py-4">
      <nav class="navbar navbar-expand-lg navbar-light">
        <a class="navbar-brand" href="#"
          ><img
            src="../assets/logo-dark.png"
            alt="logo"
            width="40%"
            class="logo"
        /></a>
        <button
          class="navbar-toggler btn"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNavDropdown"
          aria-controls="navbarNavDropdown"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class=""><i class="fas fa-bars bar"></i></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#">Our Company</a>
            </li>
            <li class="nav-item">
              <a class="nav-link ml-md-4" href="#">Locations</a>
            </li>
            <li class="nav-item">
              <a class="nav-link ml-md-4" href="#">Contact</a>
            </li>
          </ul>
        </div>
      </nav>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.nav-link {
  text-transform: uppercase;
  color: #000 !important;
  letter-spacing: 2px;
  font-size: 16px;
  font-weight: 400;
}
.navbar {
  padding: 0 !important;
  margin: 0 !important;
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .logo {
    width: 13rem;
  }
  .bar {
    color: #000;
    font-size: 30px;
  }
  .btn,
  .btn:focus {
    border: 0;
    box-shadow: none !important;
  }
}
</style>