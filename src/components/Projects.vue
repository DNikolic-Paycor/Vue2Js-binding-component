<template>
  <div id="projects">
    <h1>PROJECTS!</h1>
    <ul class="projectsList">
      <template v-for="(index,item) in images">
          <li><img :src="images[item]" :alt="item"><a href="#">Project {{item}}</a></li>
            <li class="divider"></li>
</template>

  </ul>

    </div>

  </div>
</template>

<script>
export default {
  name: 'cv',
  data () {
    return {
      images:[
      "./static/logo.png",
      "./static/logo.png",
      "./static/logo.png"




      ]

    }
  }
}

</script>

<style >

#projects h1{
  text-align: center;
  color: white;
}



.projectsList{
  text-align: center;

}
.projectsList li{
  border:1px solid grey;
  background-color: white;
  display:inline-table;
  margin:0px auto;
  padding:10px 10px;
  list-style-type: none;




}
.projectsList li a{
  color: black;
  text-align: center;
  text-decoration: none;
  display:list-item;
}

.projectsList img{
  width:250px;
  height: 250px;
}





</style>
