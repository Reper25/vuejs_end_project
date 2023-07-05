<template>
  <div>
      <nav class="navbar navbar-expand-lg bg-body-tertiary">
          <div class="container-fluid">
            <router-link to="/"><img src="https://i.postimg.cc/13hf2Cpf/Screenshot-2023-07-05-145312-removebg-preview.png" alt="LOGO" loading="lazy" class="logo"></router-link>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                <li class="nav-item">
                  <router-link to="/" class="nav-link">Home</router-link>
                </li>
                <li class="nav-item ">
                  <router-link to="/about" class="nav-link">About</router-link>
                </li>
                <li class="nav-item ">
                  <router-link to="/resume" class="nav-link">Resume</router-link>
                </li>
                <li class="nav-item ">
                  <router-link to="/testimonial" class="nav-link">Testimonial</router-link>
                 </li>
                 <li class="nav-item">
                  <router-link to="/projects" class="nav-link">Projects</router-link>
                  </li>
                  <li class="nav-item">
                   <router-link to="/contact" class="nav-link">Contact Us</router-link>
                   </li>
              </ul>
            </div>
          </div>
        </nav>
  </div>
</template>

<script>
  export default {
  }
</script>

<style scoped>
ul li a{
 margin: 5px;
}
.collapse{
  z-index: 2;
}
.navbar{
  background-color: darkgray!important;
}
/* .logo{

} */

</style>