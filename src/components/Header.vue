<template>
  <div>
      <div class="head">
            <div class="headText">
                <h1>Dragan </h1>
              <h2>Nikolic</h2>
            </div>

                <ul class="nav">
                   <li v-on:click="setComp('Home')"><a href="#head">Home</a></li>
                       <li v-on:click="setComp('Cv')"><a href="#cv">Cv</a></li>
                           <li v-on:click="setComp('BehindData')"><a href="#behindData">Behind Data</a></li>
                       <li v-on:click="setComp('Projects')"><a href="#projects">Projects</a></li>
                 <li v-on:click="setComp('Contact')"><a href="#contact">Contact</a></li>
               </ul>
           </div>

      <div class="textBox" >
          <component v-bind:is="component"></component>
        </div>

</div>

</template>

<script>

import Home from "./Home.vue";
import Cv from "./Cv.vue";
import BehindData from "./BehindData.vue";
import Projects from "./Projects.vue";
import Contact from "./contact.vue";

export default {

  components: {
    "Home":Home,
    "Cv":Cv,
    "BehindData":BehindData,
    "Projects":Projects,
    "Contact":Contact
  },

  data () {
    return {
      component:"Home"
    }
  },



      methods:{
         setComp:function(comp){
             this.component=comp;
             }
          }

    }



</script>

<style>

.head{
  width:100%;
  height: auto;
  background-color: white;
}

.headText{

  width:25%;
  color:black;
  border-left: 2px solid white;
  padding:5px;
  margin:0;
  float:left;
  background-color:inherit;
  color:#172326;
  padding:5px;
  letter-spacing: -2px;
  line-height: .4;
}
.headText h2{
  color:grey;
  letter-spacing: -1px;
}

.nav {
    background-color:/*#deecef;*/ inherit;
    list-style: none;
    margin:0;
    padding: 0;
    float: right;


}

  .nav  li{
    text-align:center;
    float:left;
    height: auto;
  }

  .nav  li  a{

    font-size: 15px;
    text-align: center;
    display:block;
    padding: 40px 20px;
    text-decoration:none;
    color:#172326;/* grey black*/
    transition: all ease .5s;
  }
  .nav a:hover{
    color: white;
    background-color:#f2435b ;/*watermellon */
  }
  .textBox {
      width:100%;
      height:500px;
      background-color:/* #32a8a8blue windows98 #caebf2; #e3e4e5 */ #979ba3;
      float:left;


    }

</style>
