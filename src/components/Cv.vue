<template>
  <div>
    <div class="personalDiv">
      <img :src="imgSrc" alt="Me" class="myImg">
        <h4>Contact</h4>
          <p>11311 Smederevo,Serbia <br>(+381) 61 637 8X XX <br> draganxxxx@gmail.com </p>
             <br>
              <h4>PersonalData</h4>
                <p>DoB:01.03.1987 <br>Maried,Father of two </p>
                  <br>
                  <h4>Languages</h4>
                   <p>Serbian,mother tongue<br>English,fluency</p>
                   <br>
            <h4>Programming</h4>
               <p>JavaScript,HTML,CSS<br>Vue2JS,Jquery,Bootstrap</p>
                  </div>
        <div class="cvText">
          <h3>Curriculum Vitae</h3>
          <h4>Education</h4>
          <p> Faculty of political Sciences,<strong>University of Belgrade,  from oct 2006 to june 2010</strong></p>
          <p> Non formal:<strong> Udemy,FreeCodeCamp,WatchAndCode..</strong></p>
          <hr>

        <h4>Work Experience </h4>
            <li>Intership at Lorem ipsum Engineering, Smederevo</li>
              <li>Part time projects at Memet ipsum,Belgrade</li>
              <hr>
        <h4>Skills</h4>
        <p>JavaScript,HTML,CSS,Vue2JS,Bootstrap,Git,GitHub</p>
        <hr>
        <h4>Summary</h4>
          <p> I am a Self-learned programer with non formal education in web development.Higly motivated for learning new skills.Enjoyig to work with Vue 2 JS.Open for part time jobs as weel as full time or remote jobs.</p>
          <hr>
        </div>



    </div>

</template>

<script>
export default {
  name: 'cv',
  data () {
    return {
      imgSrc:"./src/assets/me.jpeg"

    }
  }
}

</script>

<style>

.myImg{
  width:150px;
  height: 150px;
  border: 1px solid white;
  margin-top: 10px;
}

.cv{
  width: 100%;
  height: 100%;
}

.personalDiv{
  margin:0;
  padding-right:10px;
  background-color:#e3e4e5  /* #41b3a3;blue win98*/;
  float:left;
  width:25%;
  height:500px;
  text-align:center;
  border-right: 1px solid #f2435b /*watermellon*/;

}
.personalDiv p{
  color:#17252a; /* navy */
  margin:0em;
  letter-spacing: -1px;
}
.personalDiv h4{
  color:black;
  margin:0em;
  letter-spacing: -1px;
  font-family: Helvetica;
}
.cvText{
  margin:0;
  color:white;
  text-align:center;
  float:right;
  width: 73%;
  height:500px;
  margin:0em;
  letter-spacing: -1px;
}
.cvText h4{
  color:black;
}

hr{
  color: #f2435b /*watermellon*/;
  margin-left: 10px;
  margin-right: 10px;
}


</style>
