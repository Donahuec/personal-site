<template>
  <div class="home">
    
    <Nav />
    <Header />

  <!--Main layout-->
  <main class="mt-5">
    <div class="container">
      <!--Section: Content-->
      <section id="about-me" class="text-center">
        <div class="row">
          <div class="col-3">
            <!-- Tab navs -->
            <div
              class="nav flex-column nav-tabs text-center"
              id="about-tabs-tab"
              role="tablist"
              aria-orientation="vertical"
            >
              <a
                class="nav-link active"
                id="about-tabs-am-tab"
                data-mdb-toggle="tab"
                href="#about-tabs-am"
                role="tab"
                aria-controls="about-tabs-am"
                aria-selected="true"
                >Who I Am</a
              >
              <a
                class="nav-link"
                id="about-tabs-do-tab"
                data-mdb-toggle="tab"
                href="#about-tabs-do"
                role="tab"
                aria-controls="about-tabs-do"
                aria-selected="false"
                >What I Do</a
              >
              <a
                class="nav-link"
                id="about-tabs-love-tab"
                data-mdb-toggle="tab"
                href="#about-tabs-love"
                role="tab"
                aria-controls="about-tabs-love"
                aria-selected="false"
                >What I Love</a
              >
            </div>
            <!-- Tab navs -->
          </div>

          <div class="col-9">
            <!-- Tab content -->
            <div class="tab-content" id="about-tabs-tabContent">
              <div
                class="tab-pane fade show active"
                id="about-tabs-am"
                role="tabpanel"
                aria-labelledby="about-tabs-am-tab"
              >
                I am a Software developer located in Burnsville Minnesota.
              </div>
              <div
                class="tab-pane fade"
                id="about-tabs-do"
                role="tabpanel"
                aria-labelledby="about-tabs-do-tab"
              >
                I currently work for General Mills, developing full-stack .NET applications.
              </div>
              <div
                class="tab-pane fade"
                id="about-tabs-love"
                role="tabpanel"
                aria-labelledby="about-tabs-love-tab"
              >
                What I love content
              </div>
            </div>
            <!-- Tab content -->
          </div>
        </div>
      <!-- Tabs navs -->

     
      </section>
      <!--Section: Content-->

      <hr class="my-5" />

      <!--Section: Content-->
      <section id="eh" class="text-center">
        <h2 class="font-weight-bold">More Good Stuff</h2>
      </section>
      <!--Section: Content-->
    </div>
  </main>
  <!--Main layout-->
  <Footer />
  
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue"
import Header from "@/components/Header.vue"
import Footer from "@/components/Footer.vue"

export default {
  name: 'Home',
  components: {
    Nav,
    Header,
    Footer
  }
}
</script>
