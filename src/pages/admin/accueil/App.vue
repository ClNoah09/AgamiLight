<template>
  <!-- Template section -->
  <div class="d-flex flex-column h-100">
    <header>
      <!-- Header section -->
      <!-- Fixed navbar -->
      <nav
        class="navbar navbar-expand-lg navbar-dark fixed-top bg-dark"
        style="background: linear-gradient(90deg, #808080 10%, #0077ff 80%)"
      >
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Agami-Light</a>
          <!-- Navbar content -->
          <div
            class="collapse navbar-collapse justify-content-end"
            id="navbarNav"
          ></div>
        </div>
      </nav>
    </header>
    <!-- Main content section -->
    <!-- Begin page content -->
    <main class="flex-shrink-0 py-5 container-fluid">
      <!-- Button Container -->
      <div
        id="buttonContainer"
        class="d-flex justify-content-center align-items-center"
      >
        <!-- Buttons for navigation -->

        <a href="#images">Images</a>
        <a href="#clients">Clients</a>
      </div>
      <!-- Images Section -->

      <h2 id="images">Images</h2>
      <div class="imgcontainer">
        <!-- Container for left and right side images -->

        <div class="left-side">
          <!-- Left side images -->

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
          <!-- Right side images -->

          <h3>Résidentiel</h3>
          <div class="residentiel">
            <!-- Residential images -->
            <!-- Image containers with delete buttons -->
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
            <!-- Industrial and Tertiary images -->
            <!-- Image containers with delete buttons -->
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
            <!-- Event images -->
            <!-- Image containers with delete buttons -->
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
      <!-- Clients Section -->

      <h2 id="clients">Clients</h2>
      <!-- Container for client forms -->

      <div class="clientcontainer">
        <!-- Client form -->
        <!-- Inputs and buttons for client details -->
        <button class="button button-pdf-img">PDF/IMG</button>
        <input type="date" />
        <input type="text" placeholder="Nom Prénom" />
        <input type="email" placeholder="Email" />
        <input type="text" placeholder="Type d'intervention" />
        <div class="button button-gray button-icon"><span>&#9998;</span></div>
        <div class="button button-green button-icon"><span>&#10003;</span></div>
        <div class="button button-red button-icon"><span>&#10005;</span></div>
      </div>

      <div class="clientcontainer">
        <!-- Client form -->
        <!-- Inputs and buttons for client details -->
        <button class="button button-pdf-img">PDF/IMG</button>
        <input type="date" />
        <input type="text" placeholder="Nom Prénom" />
        <input type="email" placeholder="Email" />
        <input type="text" placeholder="Type d'intervention" />
        <div class="button button-gray button-icon"><span>&#9998;</span></div>
        <div class="button button-green button-icon"><span>&#10003;</span></div>
        <div class="button button-red button-icon"><span>&#10005;</span></div>
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
