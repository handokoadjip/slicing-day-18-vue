<template>
  <div class="container-fluid me-5 pe-5 mb-5 pb-5">
    <div class="row pb-5">
      <div class="col-lg-12 p-0">
        <div class="wrapper d-flex align-items-end h-100 position-relative">
          <figure class="m-0">
            <img class="h-image-100vh w-100" src="@/assets/source/image/img-3.jpg" alt="image-3">
          </figure>
          <div class="card rounded-0 border-0 w-lg-50 w-100 position-absolute top-50 end-0 translate-middle-y me-5">
            <div class="card-body p-5 ms-3 ms-lg-0">
              <div class="d-flex flex-column h-100">
                <p class="fw-bold mb-5">Upcomming class</p>
                <h2 class="fw-bold mb-4">
                  Pottery Making
                </h2>
                <p class="mb-5 pb-3 border-bottom">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus, culpa quas?
                </p>
                <div class="cta">
                  <router-link class="d-flex justify-content-between align-items-center pb-3" to="#">Get your spot
                    <i class="fa fa-arrow-right"></i>
                  </router-link>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "UpcomingClassComponent",
}
</script>