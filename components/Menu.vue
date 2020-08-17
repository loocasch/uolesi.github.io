<template>
  <div class="container-fluid wrapper-box">
    <scrollactive :modify-url="false" :scroll-offset="120" :offset="120">
      <div class="navbar navbar-expand-sm navbar-light bg-light wrapper-box">
        <a
          class="navbar-brand font-lora font-size-35 font-weight-bold scrollactive-item"
          href="#carousel-fade"
          >U OLESI</a
        >
        <button
          v-b-toggle.collapsibleNavId
          class="navbar-toggler d-lg-none"
          type="button"
          data-toggle="collapse"
          data-target="#collapsibleNavId"
          aria-controls="collapsibleNavId"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <b-collapse id="collapsibleNavId" class="navbar-collapse">
          <ul class="navbar-nav mr-auto mt-2 mt-lg-0 mx-auto">
            <li class="nav-item">
              <a
                class="nav-link scrollactive-item text-uppercase font-size-18"
                href="#menu"
                >Menu</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link scrollactive-item text-uppercase font-size-18"
                href="#rental"
                >Wypożyczalnia</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link scrollactive-item text-uppercase font-size-18"
                href="#gallery"
                >Galeria</a
              >
            </li>
            <li class="nav-item">
              <a
                class="nav-link scrollactive-item text-uppercase font-size-18"
                href="#contact"
                >Kontakt</a
              >
            </li>
          </ul>
        </b-collapse>
      </div>
    </scrollactive>
  </div>
</template>
<script>
export default {}
</script>
