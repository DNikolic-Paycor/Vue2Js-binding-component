<template>

  <div>
    <div class="bdata">
      <h1>Behind Data</h1>
      <div class="personal">
        <ul v-for="i in personal">
          <li>{{i}}</li>
        </ul>
        </div>

    </div>
    <div class="bText">
      <p>

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
Section 1.10.32 of "de Finibus Bonorum et Malorum", written by Cicero in 45 BC.<br><br>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?"
        </p>
    </div>

</div>
</template>

<script>
export default {

  data () {
    return {
      personal:["HUSBAND","FATHER","WEB DEVELOPER","MUSICIAN","NINTENDO FAN","NATURE LOVER","BASS GUITAR PLAYER","SOCIAL WORKER"],

    }
  }
}

</script>

<style>
.bdata{
  color: white;
  text-align: center;
}
.personal{
  float:left;
  border-right: 1px solid #e3e4e5;
}
.personal ul{
  list-style-type: none;


}
.personal li{
  padding-right:  10px;
  color:#e3e4e5;
  font-family: Helvetica;
  text-align: right;
  display: block;
}
.bText{
  color:white;
  font-style: oblique;
  margin-left: 250px;
}







</style>
