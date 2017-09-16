<template>
  <div>
    <div class="header">
      <h2>Contact!</h2>
    </div>
    <form class="contactForm">

            <input type="text" name="name" placeholder="Name">
              <input type="text" name="email" placeholder="Email">
          <textarea name="text" rows="8" cols="80" placeholder="Message"></textarea><br>

        <input type="submit" id="input-submit" value="SUBMIT">
      </form>

  </div>
</template>

<script>
export default {
  name: 'contact',
  data () {
    return {



    }
  }
}

</script>

<style>

.contactForm{
  background-color:inherit;
  max-width:600px;
  text-align: center;
  margin: 10px auto;


}

input , textarea{
     border:0; outline:0;
     padding: 1em;
     border-radius:5px;
     display: block;
     margin-top: 1em;
     width:100%;

}
textarea {
      max-height: 100px;
      max-width: 600px;
  }

.header{
  background-color: inherit;
  text-align: center;
}

#input-submit {
     color: white;
     background:#f2435b /*watermellon*/;
     cursor: pointer;
   }




</style>
