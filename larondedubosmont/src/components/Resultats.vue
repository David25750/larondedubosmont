<template>
  <div id="resultats">
    <div class="container-fluid pt-5">
      <div class="row mt-5 mb-5">
        <img class="img-fluid" src="https://parametre.davidphilippe.fr/wp-content/gallery/illustration_haut-de-page/angela-loria-ZAy8srF4rRM-unsplash.png" alt="imahe">

        <!--<div id="image-resultat" class="img-fluid" style="background-image:url(https://parametre.davidphilippe.fr/wp-content/gallery/2019/IMGP1254.JPG)"><img src="src/assets/images/image_contact.jpg" alt="" /></div>-->
        <svg id="banderole-resultat" class="position-absolute w-50 " xmlns="http://www.w3.org/2000/svg" width="944.333" height="148.973" viewBox="0 0 944.333 148.973">
          <g id="Tracé_76" data-name="Tracé 76" fill="#2e2828">
            <path d="M0,0H944.333L842,148.973H0Z" stroke="none"/>
            <path d="M 1 1.000030517578125 L 1 147.9725036621094 L 841.4737548828125 147.9725036621094 L 942.432373046875 1.000030517578125 L 1 1.000030517578125 M 0 3.0517578125e-05 L 944.33251953125 3.0517578125e-05 L 842 148.9725036621094 L 0 148.9725036621094 L 0 3.0517578125e-05 Z" stroke="none" fill="rgba(112,112,112,0)"/>
          </g>
          <text id="RESULTAT" transform="translate(311 39.486)" fill="#eee" font-size="60" font-family="Archivo-BlackItalic, Archivo" font-weight="800" font-style="italic"><tspan x="0" y="53">RESULTAT</tspan></text>
        </svg>

      </div>
    </div>
    <div class="container pt-5">
      <div class="row mt-5">
        <h2 class="display-4 text-uppercase text-center m-5">podium de l'édition</h2>
      </div>
    </div>
    <div class="row row-cols-3 mt-5 px-5">
      <div class="col mt-3 py-3 bg-success" id="deux">
        <p class="display-5 pt-3 text-center text-white">SLIMANE Mehdi</p>
      </div>
      <div class="col  py-3 bg-success" id="prem">
        <p class="display-5 text-center text-white">ALTMEYER Yoann</p>
      </div>
      <div class="col mt-4 py-3 bg-success" id="troi">
        <p class="display-5 pt-5 text-center text-white">DIDIOT Lucien</p>
      </div>
    </div>
    <div class="row row-cols-3 mb-5 px-5">
      <div class="col  p-3 bg-dark">
        <h5 class="text-center display-6 text-white text-uppercase">seconde place</h5>
      </div>
      <div class="col p-3 bg-dark">
        <h4 class="text-center display-6 text-uppercase text-warning"><strong>première place</strong></h4>
      </div>
      <div class="col p-3 bg-dark">
        <h5 class="text-center display-6 text-white text-uppercase">troisième place</h5>
      </div>
    </div>
    <div class="container-fluid bg-dark p-5 my-5">
      <div class="row">
        <h2 class="text-uppercase text-white text-center display-3 py-3">classement de l'édition 2022</h2>
      </div>
      <div class="row">
        <h3 class="text-uppercase text-white text-center display-5 py-5">la course des as</h3>
      </div>
      <div class="table-responsive text-center mx-5 border border-3 border-dark">
        <table class="table table-striped table-sm bg-white">
          <thead>
          <tr>
            <th scope="col"><p class="lead text-uppercase">Position</p></th>
            <th scope="col"><p class="lead text-uppercase">Coureur</p></th>
            <th scope="col"><p class="lead text-uppercase">Club</p></th>
            <th scope="col"><p class="lead text-uppercase">Catégorie</p></th>
            <th scope="col"><p class="lead text-uppercase">Temps</p></th>
          </tr>
          </thead>
          <tbody>
          <tr v-for="Coureur in listeCoureur" :key="Coureur.id">
            <td>{{Coureur.acf.position}}</td>
            <td>{{Coureur.acf.nom}} {{Coureur.acf.prenom}}</td>
            <td>{{Coureur.acf.club}}</td>
            <td>{{Coureur.acf.categorie}}</td>
            <td>{{Coureur.acf.temps}}</td>
          </tr>
          </tbody>
        </table>
      </div>
      <div class="container-fluid py-5 bg-dark">
        <div class="row">
          <p class="text-center text-white">Voir l'intégralité du classement</p>
        </div>
        <div class="d-grid gap-2 d-sm-flex justify-content-sm-center p-3"><a href="#" download="#">
          <b-button
                    type="submit" class="btn btn-warning text-black px-5 gap-3">Classement intégrale</b-button></a>
        </div>
      </div>
      <div class="container bg-white">
        <div class="row">
          <h1 class="text-center text-uppercase display-5 my-5">Mentions honorable</h1>
        </div>

        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3 pb-4">

          <div class="col p-3">
            <div class="card border-0">
              <a href="https://parametre.davidphilippe.fr/wp-content/uploads/2022/01/1c-Trace-Course-des-As-Ronde-du-Bosmont-Parcours-Danjoutin-2020-version-piste-cyclable.pdf" class="card text-center bg-success text-center justify-content-center align-items-center text-decoration-none">
                <div class="card-body align-items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="65" height="150" viewBox="0 0 358.622 192.481">
                    <g id="Rectangle_41" data-name="Rectangle 41" transform="translate(358.622) rotate(90)" fill="#297319" stroke="rgba(112,112,112,0)" stroke-width="1">
                      <rect width="192.481" height="358.622" stroke="none"/>
                      <rect x="0.5" y="0.5" width="191.481" height="357.622" fill="none"/>
                    </g>
                  </svg>
                </div>
                <h2 class="position-absolute di text-uppercase  text-white">ANDREY Marie-Laure</h2>
                <h4 class="card-title text-uppercase text-white"><strong>Meilleur femme</strong></h4>
              </a>
            </div>
          </div>

          <div class="col p-3">
            <div class="card border-0">
              <a href="https://parametre.davidphilippe.fr/wp-content/uploads/2022/01/1c-Trace-Course-des-As-Ronde-du-Bosmont-Parcours-Danjoutin-2020-version-piste-cyclable.pdf" class="card text-center bg-success text-center justify-content-center align-items-center text-decoration-none">
                <div class="card-body align-items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="65" height="150" viewBox="0 0 358.622 192.481">
                    <g id="Rectangle_41" data-name="Rectangle 41" transform="translate(358.622) rotate(90)" fill="#297319" stroke="rgba(112,112,112,0)" stroke-width="1">
                      <rect width="192.481" height="358.622" stroke="none"/>
                      <rect x="0.5" y="0.5" width="191.481" height="357.622" fill="none"/>
                    </g>
                  </svg>
                </div>
                <h2 class="position-absolute di text-uppercase  text-white">LE BON Marc</h2>
                <h4 class="card-title text-uppercase text-white"><strong>Doyen de la course</strong></h4>
              </a>
            </div>
          </div>

          <div class="col p-3">
            <div class="card border-0">
              <a href="https://parametre.davidphilippe.fr/wp-content/uploads/2022/01/1c-Trace-Course-des-As-Ronde-du-Bosmont-Parcours-Danjoutin-2020-version-piste-cyclable.pdf" class="card text-center bg-success text-center justify-content-center align-items-center text-decoration-none">
                <div class="card-body align-items-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="65" height="150" viewBox="0 0 358.622 192.481">
                    <g id="Rectangle_41" data-name="Rectangle 41" transform="translate(358.622) rotate(90)" fill="#297319" stroke="rgba(112,112,112,0)" stroke-width="1">
                      <rect width="192.481" height="358.622" stroke="none"/>
                      <rect x="0.5" y="0.5" width="191.481" height="357.622" fill="none"/>
                    </g>
                  </svg>
                </div>
                <h2 class="position-absolute di text-uppercase  text-white">BELFORT ATHLÉ</h2>
                <h4 class="card-title text-uppercase text-white"><strong>Meilleur Club</strong></h4>
              </a>
            </div>
          </div>
        </div>

      </div>


    </div>
  </div>
</template>


<script>

import param from "./param/param.js";

export default {
  name: "Resultats",
  data () {
    return {
      listeCoureur:[],
    }
  },
  computed: {
    listeOrderByName: function(){
      function compare(a, b) {
        if (a.acf.position < b.acf.position) return 1;
        if (a.acf.position > b.acf.position) return -1;
        return 0;
      }
      return this.listeCoureur.sort(compare);
    }


  },
  created(){
  //Liste des coureurs
    axios.get(param.host+"Coureur")
      .then(response=>{
        console.log("Response", response);
        // Récupération de la liste des participants
        this.listeCoureur = response.data;

      })
      .catch(error => console.log(error))

  }
}
</script>

<style scoped>

#banderole-resultat {
  top: 18vw;
}

</style>
