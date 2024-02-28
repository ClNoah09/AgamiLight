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
          ></div>
        </div>
      </nav>
    </header>

    <!-- Begin page content -->
    <main class="flex-shrink-0 py-5 container-fluid">
      <div
        id="buttonContainer"
        class="d-flex justify-content-center align-items-center"
      >
        <button type="button" class="btn btn-primary">Images</button>
        <button type="button" class="btn btn-primary">Clients</button>
        <button type="button" class="btn btn-primary">Agenda</button>
      </div>
    </main>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";

onMounted(() => {
  positionButtons();
  window.addEventListener("resize", positionButtons);
});

const positionButtons = () => {
  const buttonContainer = document.getElementById("buttonContainer");
  const windowHeight = window.innerHeight;
  const containerHeight = buttonContainer.clientHeight;
  const marginTop = (windowHeight - containerHeight) / 2;
  buttonContainer.style.marginTop = `${marginTop}px`;
};
</script>

<style>
#app {
  height: 100vh;
}
</style>
