<template>
  <div id="app" class="text-dark">
    <div class="justify-center items-center">
      <div style="">
      <img src="./assets/images/bg.png" style="width: 100%">
      <img src="./assets/images/sample.png" class="w-6/12 h-6/6 sample" /> 
      </div>
      <Header />
    </div>
    <Write/>
    <Stack/>
    <Cards/>
    <Mint/>
    <Alpha/>
    <Daiko/>
    <Playable/>
    <Team/>
    <Roadmap/>
    <Footer/>
    <!-- <router-view /> -->
  </div>
</template>

<script>
import Header from "./layout/Header.vue";
import Write from "./layout/Write.vue";
import Stack from "./layout/Stack.vue";
import Cards from "./layout/Cards.vue";
import Mint from "./layout/Mint.vue";
import Alpha from "./layout/Alpha.vue";
import Daiko from "./layout/Daiko.vue";
import Playable from "./layout/Playable.vue";
import Team from "./layout/Team.vue";
import Roadmap from"./layout/Roadmap.vue"
import Footer from"./layout/Footer.vue"


export default {
  name: "App",
  components: {
    Header,
    Write,
    Stack,
    Cards,
    Mint,
    Alpha,
    Daiko,
    Playable,
    Team,
    Roadmap,
    Footer,
  },
};
</script>
