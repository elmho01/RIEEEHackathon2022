<template>
<main>
  <div>
    <NavBar />
    </div>
<div>
  <b-jumbotron header="Meeting" lead="Come join us! All are welcome">
    <p>For more information:</p>
    <b-button variant="primary" target="_blank" href="https://www.instagram.com/ru_eia">See details</b-button>
  </b-jumbotron>
</div>
<div class="push"></div>
<div class="cal-wrapper">
  <b-calendar today-variant="info" v-model="value" :date-info-fn="dateClass" selected-variant="success" block locale="en-US" nav-button-variant="primary" ></b-calendar>
</div>

<div class="push"></div>
  <Footer />

</main>
</template>

<script>
export default {
  name: 'EventsPage',
    data() {
      return {
        value: ''
      }
    },
    methods: {
      dateClass(ymd, date) {
        const day = date.getDate()
        return day >= 10 && day <= 20 ? 'table-info' : ''
      }
    }
  }
</script>
<style>
.push {
  height: 50px;
}
.cal-wrapper{
  background-color: white;;
}
</style>