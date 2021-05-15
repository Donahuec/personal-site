<template>
     <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
      <div class="container-fluid">
        <!-- Navbar brand -->
        <a class="navbar-brand" href="#">
          <strong>Caitlin Donahue</strong>
        </a>

        <button class="navbar-toggler" type="button" data-mdb-toggle="collapse" data-mdb-target="#siteNavigation"
          aria-controls="siteNavigation" aria-expanded="false" aria-label="Toggle navigation">
          <i class="fas fa-bars"></i>
        </button>
        
        <div class="collapse navbar-collapse" id="siteNavigation">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link" to="/">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/resume">Resume</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/projects">Projects</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/art">Art</router-link>
            </li>
          </ul>

          <ul class="navbar-nav d-flex flex-row">
            <!-- Icons -->
            <li class="nav-item me-3 me-lg-0">
              <a class="nav-link" href="https://www.linkedin.com/in/donahuec/" rel="nofollow" target="_blank">
                <i class="fab fa-linkedin"></i>
              </a>
            </li>
            <li class="nav-item me-3 me-lg-0">
              <a class="nav-link" href="https://twitter.com/TakenFlyght" rel="nofollow" target="_blank">
                <i class="fab fa-twitter"></i>
              </a>
            </li>
            <li class="nav-item me-3 me-lg-0">
              <a class="nav-link" href="https://github.com/donahuec" rel="nofollow" target="_blank">
                <i class="fab fa-github"></i>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'Nav'
}
</script>

 <style>
 .navbar .nav-link {
    color: #fff !important;
  }
 </style>