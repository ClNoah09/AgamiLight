<script setup></script>

<template>
  <div class="d-flex flex-column h-100">
    <header>
      <!-- Fixed navbar -->
      <nav
        class="navbar navbar-expand-lg navbar-dark fixed-top bg-dark"
        style="background: linear-gradient(90deg, #808080 10%, #0077ff 80%)"
      >
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
    <main class="flex-shrink-0 py-5 container-fluid">
      <div id="carouselExample" class="carousel slide nav">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img
              src="./assets/electricien-masculin-travaille-dans-standard-cable-raccordement-electrique (1).jpg"
              class="d-block w-100"
              alt="..."
            />
          </div>
          <div class="carousel-item">
            <img src="..." class="d-block w-100" alt="..." />
          </div>
          <div class="carousel-item">
            <img src="..." class="d-block" alt="..." />
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExample"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExample"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <div class="logo d-flex justify-content-center">
        <img src="./assets/LOGO_NEGATIF.PNG" alt="LOGO" class="img-fluid" />
      </div>

      <button type="button" class="btn btn-primary mt-2 mb-0">
        Me Contacter
      </button>
      <!---SECTEUR D4ACTIVITE-->
      <div class="container-fluid p-0">
        <div class="row">
          <div class="col-md-12 text-center mt-3">
            <div class="rectangle">
              <p>Secteur d'activités</p>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 custom-div d-flex align-items-center">
            <div
              id="carouselExampleRide"
              class="carousel slide"
              data-bs-ride="carousel"
              data-interval="false"
            >
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img
                    src="https://via.placeholder.com/800x600.png?text=Slide+1"
                    class="d-block w-100 h-100"
                    alt="Slide 1"
                  />
                </div>
                <div class="carousel-item">
                  <img
                    src="https://via.placeholder.com/800x600.png?text=Slide+2"
                    class="d-block w-100 h-100"
                    alt="Slide 2"
                  />
                </div>
                <div class="carousel-item">
                  <img
                    src="https://via.placeholder.com/800x600.png?text=Slide+3"
                    class="d-block w-100 h-100"
                    alt="Slide 3"
                  />
                </div>
              </div>
              <button
                class="carousel-control-prev"
                type="button"
                data-bs-target="#carouselExampleRide"
                data-bs-slide="prev"
              >
                <span
                  class="carousel-control-prev-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button
                class="carousel-control-next"
                type="button"
                data-bs-target="#carouselExampleRide"
                data-bs-slide="next"
              >
                <span
                  class="carousel-control-next-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
          <div
            class="col-md-6 d-flex align-items-center"
            style="background-color: #0077ff"
          >
            <p class="m-4">
              En tant qu'électricien, je m'occupe de l'installation et de la
              maintenance des systèmes électriques. Mon travail va du
              résidentiel au tertiaire, industriel et événementiel. Je veille à
              ce que les installations soient sûres et fonctionnent correctement
              dans divers environnements.
            </p>
          </div>
        </div>
      </div>

      <div class="container">
        <div class="icon">
          <img src="./assets/house-solid.svg" alt="Maison" />
          <div class="description">Résidentiel</div>
        </div>
        <div class="icon">
          <img src="./assets/building-regular.svg" alt="Bâtiments" />
          <div class="description">Tertiaire et Industrielle</div>
        </div>
        <div class="icon">
          <img
            src="./assets/stadium_FILL0_wght400_GRAD0_opsz24.svg"
            alt="Stade"
          />
          <div class="description">Evénementiel</div>
        </div>
      </div>
    </main>

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
