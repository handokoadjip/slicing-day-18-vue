<template>
  <footer class="py-5">
    <div class="container border-top-fade-black-1-2px py-5 my-5">
      <div class="row w-100 pt-5">
        <div class="col-lg-4 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <h3 class="fs-4 fw-bold mb-4">Pyottros</h3>
            <p class="fw-medium">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
            </p>
          </div>
        </div>
        <div class="offset-lg-2 col-lg-2 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <h3 class="fs-6 fw-medium text-fade-black-1 mb-4">Company</h3>
            <nav>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">About</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Articles</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Classes</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-2 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <h3 class="fs-6 fw-medium text-fade-black-1 mb-4">Support</h3>
            <nav>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Help Center</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Contact us</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Cookies</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Privacy & terms</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">FAQs</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-2 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <h3 class="fs-6 fw-medium text-fade-black-1 mb-4">Social</h3>
            <nav>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Instagram</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Twitter</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Facebook</router-link>
              <router-link class="text-decoration-none fw-medium mb-3 d-block" to="#">Youtube</router-link>
            </nav>
          </div>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row align-items-center h-vh-30 py-5">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="copyright d-block d-lg-flex justify-content-lg-between align-items-lg-center text-center">
              <div class="mb-5 mb-lg-0">
                <p class="mp-0">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quos, sed.</p>
              </div>
              <ul class="text-uppercase d-inline mp-0">
                <li class="d-inline">
                  <router-link class="nav-link fw-bold d-lg-flex align-items-center d-block" to="#">
                    Back to top
                    <i class="ms-3 fa fa-arrow-up"></i>
                  </router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>