<template>

      <div>
        <div>
            <div class="helloText">
              <h1>&lt&gtHello<span style="color:black">World!</span>&lt/&gt</h1>
           </div>
           <div class="pText">
             <p>I am a Front End Developer and i love to build a beautiful thinghs with VueJS!</p>

           </div>
           </div>
        </div>
  
</template>
  <script>
    export default {
      name: 'home',
      data () {
        return {


        }
      }
    }

    </script>


<style>

.helloText{
  border-radius: 3px;
  text-align: center;
  margin-bottom: 0;
  margin-top: 100px;
  margin-left: auto;
  margin-right: auto;
  width:550px;
  background-color:white;
  padding: 20px;
  font-size: 25px;
  color:#a0b3ba;
  letter-spacing: -2px;
}


.pText{
  border-radius: 3px;
  padding: 5px;
  margin-left:30%;
  margin-right: 30%;
  background-color:#f2435b /*watermellon*/;
  color:black;/* #adadad carbon*/;
  letter-spacing: -1px;
  text-align: center;

}


.component-fade-enter-active, .component-fade-leave-active {
  transition: opacity .6s;
}
.component-fade-enter, .component-fade-leave-to
/* .component-fade-leave-active below version 2.1.8 */ {
   opacity: 0;
}

</style>
