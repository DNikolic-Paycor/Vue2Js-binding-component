<template>
  <div>
    <app-head></app-head>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Home from "./components/Home.vue";
import Cv from "./components/Cv.vue";
import BehindData from "./components/BehindData.vue";
import Projects from "./components/Projects.vue";
import Contact from "./components/contact.vue";


export default {

  components: {
    "app-head":Header,
    "Home":Home,
    "Cv":Cv,
    "BehindData":BehindData,
    "Projects":Projects
  },
  data () {


  },
    methods:{

    }
  }

</script>

<style>
body

{
  padding:0px;
  width:100%;
  height:100%;
  margin:0%;
}




</style>
