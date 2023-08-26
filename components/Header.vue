<template>
<nav class="navbar navbar-expand-lg bg-body-tertiary fixed-top">
  <div class="container-fluid">
    <router-link to="/" class="navbar-brand">Pendongeng</router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav m-auto">
        <router-link to="/" class="nav-link">Home</router-link>
        <router-link to="/about" class="nav-link">About</router-link>
        <router-link to="/contact" class="nav-link">Contact</router-link>
      </div>
    </div>
  </div>
</nav>
</template>