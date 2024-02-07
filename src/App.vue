<script setup></script>

<template>
  <div class="d-flex flex-column h-100">
    <header>
      fixed-top bg-dark
      <!-- Fixed navbar -->
      <nav class="navbar navbar-expand-lg navbar-dark fixed-top bg-dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Agami-Light</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="collapse navbar-collapse justify-content-end"
            id="navbarNav"
          >
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" href="#">Secteur d'activités</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Témoiniage</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Photos</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Evenements</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>

    <!-- Begin page content -->
    <main class="flex-shrink-0 py-5"></main>

    <footer class="footer mt-auto py-3 bg-blue">
      <div class="container-fluid">
        <div class="row align-items-center">
          <div class="col-4 text-start">
            <p class="mb-0">2024 Agami-Light.be</p>
          </div>
          <div class="col-4 text-center">
            <img
              src="./assets/LOGO_NEGATIF.png"
              alt="Logo"
              class="img-fluid smaller-image"
            />
          </div>

          <div class="col-4 text-end">
            <a href="mentions-legales.html" class="text-dark"
              >Mentions légales</a
            >
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
#app {
  height: 100vh;
}
</style>
