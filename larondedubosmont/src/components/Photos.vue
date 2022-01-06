<template>
<div id="photos">
  <div class="container-fluid pt-5 p-5 bg-dark">
    <div class="row mt-5">
      <h1 class="display-4 text-center text-uppercase m-5 text-white">photo de notre dernière édition</h1>
    </div>
    <b-carousel
      id="carousel-1"
      class="m-5"
      v-model="slide"
      :interval="3000"
      controls
      indicators
      img-width="390"
      img-height="240"
      style="text-shadow: 1px 1px 2px #333;"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >

      <!-- Slides with custom text -->
      <b-carousel-slide img-src="https://parametre.davidphilippe.fr/wp-content/gallery/2019/IMGP1254.JPG">
        <h1>2019</h1>
      </b-carousel-slide>
      <b-carousel-slide img-src="https://parametre.davidphilippe.fr/wp-content/gallery/2019/IMGP1256.JPG">
        <h1>2019</h1>
      </b-carousel-slide>
      <b-carousel-slide img-src="https://parametre.davidphilippe.fr/wp-content/gallery/2019/IMGP1263.JPG">
        <h1>2019</h1>
      </b-carousel-slide>
    </b-carousel>
  </div>
  <div class="container">
    <div class="row">
      <h4 class="display-6 text-uppercase text-center my-5">Albums des éditions précédentes</h4>
    </div>
    <div class="row">
      <p class="lead text-center my-5">Dans ces albums, vous retrouverez les photos des éditions précédentes. Grâce à ses archives photos uniques, retournez dans le passé de notre évènement  la Ronde du Bosmont.</p>
    </div>
  </div>
  <div class="container">

    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">

      <div class="col">
        <div class="card shadow-sm border ">
          <a href="https://parametre.davidphilippe.fr/2019-2/" class="card-body text-decoration-none text-black">
            <p class="card-title display-6 text-center text-uppercase border-bottom border-2 border-dark">2019</p>
            <img src="https://parametre.davidphilippe.fr/wp-content/gallery/2019/IMGP1263.JPG" class="card-img img-fluid card" alt="2019">
            <svg class="" xmlns="http://www.w3.org/2000/svg" width="100%" height="41" viewBox="0 0 564 41">
              <g id="bande" transform="translate(-89 -1712)">
                <g id="Rectangle_79" data-name="Rectangle 79" transform="translate(89 1712)" fill="#2e2828" stroke="rgba(112,112,112,0)" stroke-width="1">
                  <rect width="564" height="41" stroke="none"/>
                  <rect x="0.5" y="0.5" width="563" height="40" fill="none"/>
                </g>
                <line id="Ligne_39" data-name="Ligne 39" y1="12" x2="19" transform="translate(362.5 1732.5)" fill="none" stroke="#C1E120" stroke-width="1"/>
                <line id="Ligne_40" data-name="Ligne 40" x2="19" y2="11" transform="translate(362.5 1721.5)" fill="none" stroke="#C1E120" stroke-width="1"/>
              </g>
            </svg>
          </a>
        </div>
      </div>

      <div class="col">
        <div class="card shadow-sm border ">
          <a href="https://parametre.davidphilippe.fr/2018-2/" class="card-body text-decoration-none text-black">
            <p class="card-title display-6 text-center text-uppercase border-bottom border-2 border-dark">2018</p>
            <img src="https://parametre.davidphilippe.fr/wp-content/gallery/2019/IMGP1263.JPG" class="card-img img-fluid card" alt="2018">
            <svg class="" xmlns="http://www.w3.org/2000/svg" width="100%" height="41" viewBox="0 0 564 41">
              <g id="bande" transform="translate(-89 -1712)">
                <g id="Rectangle_79" data-name="Rectangle 79" transform="translate(89 1712)" fill="#2e2828" stroke="rgba(112,112,112,0)" stroke-width="1">
                  <rect width="564" height="41" stroke="none"/>
                  <rect x="0.5" y="0.5" width="563" height="40" fill="none"/>
                </g>
                <line id="Ligne_39" data-name="Ligne 39" y1="12" x2="19" transform="translate(362.5 1732.5)" fill="none" stroke="#C1E120" stroke-width="1"/>
                <line id="Ligne_40" data-name="Ligne 40" x2="19" y2="11" transform="translate(362.5 1721.5)" fill="none" stroke="#C1E120" stroke-width="1"/>
              </g>
            </svg>
          </a>
        </div>
      </div>

      <div class="col">
        <div class="card shadow-sm border ">
          <a href="https://parametre.davidphilippe.fr/2022-2/" class="card-body text-decoration-none text-black">
            <p class="card-title display-6 text-center text-uppercase border-bottom border-2 border-dark">2012</p>
            <img src="https://parametre.davidphilippe.fr/wp-content/gallery/2019/IMGP1263.JPG" class="card-img img-fluid card" alt="2019">
            <svg class="" xmlns="http://www.w3.org/2000/svg" width="100%" height="41" viewBox="0 0 564 41">
              <g id="bande" transform="translate(-89 -1712)">
                <g id="Rectangle_79" data-name="Rectangle 79" transform="translate(89 1712)" fill="#2e2828" stroke="rgba(112,112,112,0)" stroke-width="1">
                  <rect width="564" height="41" stroke="none"/>
                  <rect x="0.5" y="0.5" width="563" height="40" fill="none"/>
                </g>
                <line id="Ligne_39" data-name="Ligne 39" y1="12" x2="19" transform="translate(362.5 1732.5)" fill="none" stroke="#C1E120" stroke-width="1"/>
                <line id="Ligne_40" data-name="Ligne 40" x2="19" y2="11" transform="translate(362.5 1721.5)" fill="none" stroke="#C1E120" stroke-width="1"/>
              </g>
            </svg>
          </a>
        </div>
      </div>


      </div>
    </div>





</div>
</template>

<script>

import param from "./param/param.js";

export default {
  name: "Photos",
  data() {
    return {
      slide: 0,
      sliding: null,
      listeAlbum: [],
    }
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true
    },
    onSlideEnd(slide) {
      this.sliding = false
    }
  },
  created() {
  }
}
</script>

<style scoped>

</style>
