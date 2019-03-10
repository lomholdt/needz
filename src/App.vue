<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/needz.png">
    <h2>mindre besvær og mere tid i din hverdag.</h2>
    <h3>Fra d. 1. april leverer vi abonnementer på hverdagsting.</h3>
    <p>Til din baby, til dit køkken, til dit badeværelse, dit kæledyr, til din sportsgren og du bestemmer selv frekvensen.
Vil du have produktet hver uge, hver anden uge, hver fjerde, hver anden måned eller hvert halve år - det er op til dig. Prisen er den du kender fra butikken, du skal ikke betale fragt og vi leverer til din hoveddør. Hvad vil DU gerne have på abonnement?
</p>
    <MailChimp></MailChimp>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MailChimp from './components/MailChimp.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    MailChimp
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
