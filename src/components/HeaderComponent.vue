<template>
  <header class="position-relative">
    <nav class="navbar navbar-expand-lg navbar-light px-4">
      <div class="container d-flex justify-content-between">
        <router-link class="navbar-brand text-center fs-2 mp-0 fw-bold ls-5px" to="#">
          Pyottros
        </router-link>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-bold" aria-current="page" to="#">home</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-bold" to="#">Articles</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-bold" to="#">About</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-bold" to="#">Classes</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section>
      <div class="container">
        <div class="row min-vh-80 pb-5">
          <div class="col-lg-8">
            <div class="wrapper d-flex align-items-end h-100">
              <div class="w-100">
                <h1 class="text-navbar fw-normal">
                  Makers
                  <br /> Workshop
                </h1>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div class="wrapper d-flex align-items-end h-100">
              <p>
                Exploring about the posibbility that happens
                <br /> when you try somthing you never tried
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

