<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="https://bulma.io">
        <img src="https://vuejs.org/images/logo.png" width="28" height="28" />
      </a>

      <a
        role="button"
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item"> Home</a>
        <a class="navbar-item"> Documentation</a>
      </div>
    </div>
    <div id="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <router-link to="/create" class="button is-dark">
            <strong>Create</strong>
          </router-link>
        </div>
      </div>
    </div>
  </nav>
</template>
<script>
export default {};
</script>

<style></style>
