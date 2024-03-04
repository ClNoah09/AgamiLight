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
      <div class="imgcontainer">
        <div class="left-side">
          <img src="https://via.placeholder.com/150" alt="Placeholder" />
          <button class="button">+</button>
          <h3>Insérez image</h3>
          <select>
            <option value="residential">Résidentiel</option>
            <option value="industrial">Industriel, Tertiaire</option>
            <option value="event">Événementiel</option>
          </select>
          <button class="approve-button">V</button>
        </div>
        <div class="right-side">
          <h3>Résidentiel</h3>
          <div class="residentiel">
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
          </div>
          <h3>Industriel et Tertiaire</h3>
          <div class="industirel">
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
          </div>
          <h3>Événementiel</h3>
          <div class="evenementiel">
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
            <div class="image-container">
              <div class="image-wrapper">
                <img
                  src="https://via.placeholder.com/100"
                  alt="Placeholder"
                  class="image"
                />
                <button class="delete-button">X</button>
              </div>
            </div>
          </div>
        </div>
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
