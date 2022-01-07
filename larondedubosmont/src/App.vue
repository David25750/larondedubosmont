<template>
  <div id="app">
    <div class="container-fluid position-absolute">
      <header class="d-flex flex-wrap justify-content-center align-content-center bg-white">
        <a href="https://rondedubosmont.davidphilippe.fr/#/" class="d-flex me-md-auto text-decoration-none">
          <svg class="w-75 mx-2" xmlns="http://www.w3.org/2000/svg" width="281.357" height="90.754" viewBox="0 0 281.357 90.754">
            <ellipse id="Ellipse_48" data-name="Ellipse 48" cx="42.9" cy="43.699" rx="42.9" ry="43.699" transform="translate(40.874 1)" fill="none" stroke="#161615" stroke-miterlimit="10" stroke-width="2"/>
            <path id="Tracé_118" data-name="Tracé 118" d="M126.384,65.062s-9.42,38.311,31.588,43.651l26.119,2.192c-2.115-.474-64.509-8.063-55.306-55.023Z" transform="translate(-46.799 -20.152)" fill="#2d6223"/>
            <path id="Tracé_119" data-name="Tracé 119" d="M88.04,58.391s14.432-4.892,12.017-17.284-16.669-13.752-23.411-8.56C63.2,42.9,74.594,71.63,56.986,75.87s-44.5-27.262-44.5-27.262L0,32.629S47.862,72.523,53.945,67.958s1.626-35,19.661-44.46c17.232-9.037,34.362.326,34.284,15.726C107.79,58.46,88.04,58.391,88.04,58.391" transform="translate(0 -7.17)" fill="#2d6223"/>
            <text id="LA_RONDE_DU_" data-name="LA RONDE DU " transform="translate(140.678 28.657)" fill="#161615" font-size="14" font-family="Archivo-BlackItalic, Archivo" font-weight="800" font-style="italic"><tspan x="0" y="0">LA RONDE DU </tspan></text>
            <text id="BOSMONT" transform="translate(137.357 57.639)" fill="#2d6223" font-size="25" font-family="Archivo-BlackItalic, Archivo" font-weight="800" font-style="italic"><tspan x="0" y="0">BOSMONT</tspan></text>
          </svg>

        </a>
        <nav class="navbar-expand-sm navbar-light bg-white">
          <div class="container-fluid">
            <div class="nav-toggle" onclick="document.documentElement.classList.toggle('menu-open')">
              <div class="nav-toggle-bar"></div>
            </div>
            <div class="menu" id="navigation">
              <ul class="navbar-nav me-auto">
                <li class="nav-item"><router-link to="/" class="nav-link active bg-white text-black-50 px-3 py-4">Accueil</router-link></li>
                <li class="nav-item"><router-link to="Information" class="nav-link bg-white text-black-50 px-3 py-4">Information</router-link></li>
                <li class="nav-item"><router-link to="Photos" class="nav-link bg-white text-black-50 px-3 py-4">Photos</router-link></li>
                <li class="nav-item"><router-link to="Resultats" class="nav-link bg-white text-black-50 px-3 py-4">Resultats</router-link></li>
                <li class="nav-item"><router-link to="Contact" class="nav-link bg-white text-black-50 px-3 py-4">Contact</router-link></li>
                <li id="lien-inscription" class="nav-item"><a href="https://www.le-sportif.com/CalendarDetail/CalendarDetail.aspx?EventID=181414"
                                                              class="nav-link active bg-success text-white  border border-3 border-0 p-4">Inscription</a></li>
              </ul>
            </div>
          </div>
        </nav>
      </header>
    </div>
    <router-view/>
    <div class="container">
      <footer class="border-top">
        <div class="row py-5 my-5 justify-content-center">
          <div class="col text-center">
            <svg class="w-75 mx-2" xmlns="http://www.w3.org/2000/svg" width="281.357" height="90.754" viewBox="0 0 281.357 90.754">
              <ellipse id="Ellipse_48" data-name="Ellipse 48" cx="42.9" cy="43.699" rx="42.9" ry="43.699" transform="translate(40.874 1)" fill="none" stroke="#161615" stroke-miterlimit="10" stroke-width="2"/>
              <path id="Tracé_118" data-name="Tracé 118" d="M126.384,65.062s-9.42,38.311,31.588,43.651l26.119,2.192c-2.115-.474-64.509-8.063-55.306-55.023Z" transform="translate(-46.799 -20.152)" fill="#2d6223"/>
              <path id="Tracé_119" data-name="Tracé 119" d="M88.04,58.391s14.432-4.892,12.017-17.284-16.669-13.752-23.411-8.56C63.2,42.9,74.594,71.63,56.986,75.87s-44.5-27.262-44.5-27.262L0,32.629S47.862,72.523,53.945,67.958s1.626-35,19.661-44.46c17.232-9.037,34.362.326,34.284,15.726C107.79,58.46,88.04,58.391,88.04,58.391" transform="translate(0 -7.17)" fill="#2d6223"/>
              <text id="LA_RONDE_DU_" data-name="LA RONDE DU " transform="translate(140.678 28.657)" fill="#161615" font-size="14" font-family="Archivo-BlackItalic, Archivo" font-weight="800" font-style="italic"><tspan x="0" y="0">LA RONDE DU </tspan></text>
              <text id="BOSMONT" transform="translate(137.357 57.639)" fill="#2d6223" font-size="25" font-family="Archivo-BlackItalic, Archivo" font-weight="800" font-style="italic"><tspan x="0" y="0">BOSMONT</tspan></text>
            </svg>
            <a href="https://parametre.davidphilippe.fr/wp-admin" class="text-success text-decoration-none mt-2">connexion</a>
          </div>
          <div class="col">
            <h5 class="mb-5">Réseaux sociaux</h5>
            <ul class="row nav mt-2">
              <li class="nav-item col p-0 m-0"><a href="https://www.facebook.com/profile.php?id=100076852294663" class="nav-link p-0 m-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" fill="#297319" class="bi bi-facebook" viewBox="0 0 16 16">
                  <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"/>
                </svg></a></li>
              <li class="nav-item col p-0 m-0"><a href="https://www.instagram.com/rondedubosmont/" class="nav-link p-0 m-0">
                <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" fill="#297319" class="bi bi-instagram" viewBox="0 0 16 16">
                  <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"/>
                </svg></a></li>
            </ul>
          </div>
          <div class="col">
            <h5>Contact</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><p>Contactez - nous pour toute information complémentaires</p></li>
              <li class="nav-item mb-2 flex-row">

                  <p class="text-black bg-white lead">03 84 56 12 05</p>

              </li>
              <li class="nav-item mb-2 ">
                <p class="text-black bg-white lead">contact@rondedubosmont.fr</p>
              </li>
            </ul>
          </div>
          <div class="col">
            <h5>Inscrivez - vous</h5>
            <ul class="nav flex-column">
              <li class="nav-item mb-2"><p>La prochaine édition est désormais ouverte aux inscription !</p></li>
              <li class="nav-item"><b-button href="https://www.le-sportif.com/CalendarDetail/CalendarDetail.aspx?EventID=174735&SHAD="
                                             type="submit" variant="success" class="btn border  text-white border-2 nav-link px-5 py-3">Je m'inscris</b-button></li>

            </ul>
          </div>
        </div>
        <div class="row mb-2 nav-link">
          <router-link to="Mentions" class="nav-item text-decoration-none text-black"><p class="text-center"> © Copyright La Ronde du Bosmont   Mentions légales   Réalisation Alexandre Anthoine Nathan Broglin et David Philippe</p></router-link>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>


</style>
