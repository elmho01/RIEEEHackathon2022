<template>
<main>
    <NavBar />

    <!-- Site Content == Between the <div> tags -->
<div class="carousel-container">
  <div class="carousel-wrapper">
   <h2 class = 'subtitle'>Eswatini, 2022</h2>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="3000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333;"
  >
      <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_8554.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_4576.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_4577.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_9390.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/20220613_085253.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/20220606_160258.jpg"
      img-height="480px"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_9866.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_9608.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_9722.jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/IMG_0010.jpg"
    ></b-carousel-slide>
 <b-carousel-slide
      caption=""
      img-src="../assets/Eswatini/2022BridgeTeam.jpg"
    ></b-carousel-slide>
  </b-carousel>


  <!-- Capiana, Bolivia -->
  <h2 class = "subtitle"> Capiana, Bolivia 2018 </h2>
  <b-carousel
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="800"
    img-height="400"
    :interval="0"
  >
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(46).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(47).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(48).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(49).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(50).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(51).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(52).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(53).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(54).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(55).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(56).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(57).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(58).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(59).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(60).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(61).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(62).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(63).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(64).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(65).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(66).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(67).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(68).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption=""
      img-src= "../assets/Capiana/(69).jpg"
    ></b-carousel-slide>

  </b-carousel>

    <h2 class = 'subtitle'>Palmar Pampa B, Bolvia 2017</h2>
    <b-carousel
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
    :interval="0"
  >
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (1).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (2).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (3).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (4).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (5).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (6).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (7).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (8).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (9).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (10).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (11).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (12).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (13).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (14).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (15).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (16).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (17).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (18).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (19).jpg"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Palmar Pampa B, Bolivia 2017"
      img-src="../assets/Palmar/Prep (20).jpg"
    ></b-carousel-slide>
  </b-carousel>
  </div>
</div>


    <!-- Site footer -->
<div class="push"></div>
    <Footer />
</main>
</template>

<script>

  export default {
    name: 'GalleryPage', 
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }

</script>
<style scoped>
.push {
  height: 50px;
}

.subtitle {
  padding-top: 35px;
  padding-bottom: 20px;
  text-align: center;
}

.carousel-container {
  width: 100%;
  height: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.carousel-wrapper {
  max-width: 90%;
}

</style>