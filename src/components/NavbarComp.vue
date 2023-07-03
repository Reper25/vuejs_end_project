<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav">
      <li class="nav-item">
        <router-link to="/">Home</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/about">about</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/resume">resume</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/projects">projects</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/testimonials">testimonial</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/contact">contact</router-link>
      </li>
    </ul>
  </div>
</nav>
</template>

<script>

export default{

}
</script>

<style>

</style>