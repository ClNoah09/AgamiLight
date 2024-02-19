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
                <a class="nav-link" href="#secteur-activites"
                  >Secteur d'activités</a
                >
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#temoignages">Témoiniage</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#evenements">Evenements</a>
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
      <div id="carouselExample " class="carousel slide nav">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img
              src="../../assets/electricien-masculin-travaille-dans-standard-cable-raccordement-electrique (1).jpg"
              class="d-block w-100"
              alt="..."
            />
          </div>
        </div>
      </div>
      <div class="Politique de confidentialité">
        <h3>Politique de confidentialité</h3>
        <p>
          Les données stockées dans ma boîte mail sont protégées par un mot de
          passe et les informations envoyées sont protégées par un encryptage
          SSL. Vos informations seront utilisées uniquement pour répondre à
          votre demande. « NathalieVanassche.be » ne stocke aucune information
          vous concernant dans une base de données.
        </p>
      </div>
      <div class="Droit d'auteur">
        <h3>Droit d'auteur</h3>
        <p>
          Le site « NathalieVanassche.be » constitue une création protégée par
          le droit d'auteur. Les textes, exercices, correctifs, photos, et
          autres éléments de ce site sont protégés par le droit d'auteur. Toute
          copie, adaptation, traduction, arrangement, communication au public,
          location et autre exploitation, modification de tout ou partie de ce
          site sous quelle que forme et par quel que moyen que ce soit,
          électronique, mécanique ou autre, réalisée dans un but lucratif, est
          strictement interdit sans mon autorisation préalable. Toute infraction
          à ces droits peut entraîner des poursuites civiles ou pénales.
          Cependant, ce site est destiné à mes étudiants et le contenu mis en
          ligne est destiné à être exploité à volonté dans un cadre privé.
          Ainsi, les copies, impressions, enregistrements sont autorisées sous
          les seules réserves de ne pas dissimuler les signes distinctifs de
          personnalisation et de ne pas en faire un usage commercial. En
          revanche, je n'assure aucune aide, ni support sur des questions
          d'utilisation ou de compréhension de tous supports disponibles sur ce
          site en dehors d'un contexte de cours.
        </p>
      </div>
      <div class="Marques et noms commerciaux">
        <h3>Marques et noms commerciaux</h3>
        <p>
          Les dénominations, logos et autres signes utilisés sur ce site sont
          des marques et/ou noms commerciaux légalement protégés. Tout usage de
          ceux-ci ou de signes ressemblants est strictement interdit sans un
          accord préalable et écrit.
        </p>
      </div>
      <div class="Responsabilité quant au contenu">
        <h3>Responsabilité quant au contenu</h3>
        <p>
          J'apporte le plus grand soin à la création et à la mise à jour de ce
          site mais je ne peux toutefois pas garantir l'exactitude de
          l'information qui s'y trouve. Les informations contenues dans ce site
          pourront faire l'objet de modifications sans préavis. Les informations
          données sur ce site ne sauraient engager ma responsabilité, je ne
          pourrais être tenue pour responsable de toute omission, erreur ou
          lacune qui aurait pu se glisser dans ses pages ainsi que des
          conséquences, quelle qu'elles soient, pouvant résulter de
          l'utilisation des informations et indications fournies.
        </p>
      </div>
      <div class="Coordonnées">
        <h3>Coordonnées</h3>
        <p>
          Vous pouvez me contacter par Email à
          nathalie.vanassche@ifosup.wavre.be à l'IFOSUP : www.ifosupwavre.be Rue
          de la Limite, 6 1300 Wavre 010/22.20.26
        </p>
      </div>
      <div class="Hébergeur">
        <h3>Hébergeur</h3>
        <p>OVH 2 rue Kellermann 59100 Roubaix - France. www.ovh.com</p>
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
              src="../../assets/LOGO_NEGATIF.png"
              alt="Logo"
              class="img-fluid smaller-image"
            />
          </div>

          <div class="col-4 text-end">
            <a href="mentions.html" class="text-dark">Mentions légales</a>
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
