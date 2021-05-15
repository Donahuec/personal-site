<template>
    <header>
    <!-- Background image -->
    <div id="intro" class="bg-image shadow-2-strong">
      <div class="mask gradient-custom">
        <div class="container d-flex align-items-center justify-content-center text-center h-100">
          <div class="row">
              <div class="col-md-5 offset-md-1 d-flex flex-column align-items-center justify-content-center">
                <img
                    src="@/assets/portrait.jpg"
                    class="shadow-2-strong rounded-circle"
                    alt="Portrait of Caitlin Donahue"
                    style="max-width: 70%; and height: auto;"
                    />
                  <h1 class="display-3 text-white row">Caitlin Donahue</h1>
                  <div class="row">
                    <div class="col-4">
                    <!-- LinkedIn -->
                      <a class="text-white" href="https://www.linkedin.com/in/donahuec/" role="button"
                        ><i class="fab fa-linkedin fa-lg"></i
                      ></a>
                    </div>
                    <div class="col-4">
                      <!-- Twitter -->
                      <a class="text-white" href="https://twitter.com/TakenFlyght" role="button"
                        ><i class="fab fa-twitter fa-lg"></i
                      ></a>
                    </div>
                    <div class="col-4">
                      <!-- GitHub -->
                      <a class="text-white" href="https://github.com/donahuec" role="button"
                        ><i class="fab fa-github fa-lg"></i
                      ></a>
                    </div>
                  </div>
                  </div>
              <div class="col-md-5 d-flex flex-column align-items-center justify-content-center">
                <dl class="row text-white">
                  <dt class="col-sm-3">What I Do</dt>
                  <dd class="col-sm-9">
                    I am a software developer, whith a passion for web and UI development. Lately I've been focused on full-stack .NET development.
                    </dd>

                  <dt class="col-sm-3">What I Love</dt>
                  <dd class="col-sm-9">UI/UX development, clean code, learning, accessibility, art, games, disibility advocacy, and more. </dd>

                  <dt class="col-sm-3">Where I Am</dt>
                  <dd class="col-sm-9">
                    <p>
                      I live in Burnsville, MN. I work in the twin-cities metro area.
                    </p>
                  </dd>
                </dl>
              </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Background image -->
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>
#intro {
        background-image: url("../assets/header-bg.jpg");
        height: 100vh;

      }

.gradient-custom {
  /* fallback for old browsers */
  background: #30cfd0;

  /* Chrome 10-25, Safari 5.1-6 */
  background: -webkit-linear-gradient(to top, rgba(48, 207, 208, 0.8), rgba(51, 8, 103, 0.8));

  /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  background: linear-gradient(to top, rgba(48, 207, 208, 0.8), rgba(51, 8, 103, 0.8))
}
</style>