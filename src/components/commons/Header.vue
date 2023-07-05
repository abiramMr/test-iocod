<template lang="html">
  <section class="header">
    <header class="fixed-top">
      <nav class="navbar navbar-expand-lg">
        <div class="container">
          <a class="navbar-brand" href="#">
            <img src="@/assets/images/Logo.png" alt="logo" />
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNavDropdown"
            aria-controls="navbarNavDropdown"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <div class="hamburger">
              <div class="bar topopen"></div>
              <div class="bar midopen"></div>
              <div class="bar botopen"></div>
            </div>
            <!-- <span class="navbar-toggler-icon"></span> -->
          </button>
          <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>

              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="navbarDropdownMenuLink"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Case Studies
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="#">Something</a></li>
                  <li><a class="dropdown-item" href="#">Something </a></li>
                  <li><a class="dropdown-item" href="#">Something</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Blog</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#"> About us</a>
              </li>
              <li class="nav-item">
                <a class="nav-link btn px-4" href="#"> Book a call</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
  </section>
</template>

<script lang="js">

export default {
  name: 'headers',
  props: [],
  setup() {
    return { };
  },
};
</script>

<style scoped lang="scss">
.header {
}
</style>
