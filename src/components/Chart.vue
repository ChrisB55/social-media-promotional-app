<template>
<v-app>
    <v-slide-y-transition mode="out-in">
      <v-layout column align-center>
        <form id="poll-form">
       <input type="radio" name="poll" id="yes" value="Yes">
          <label for="yes">Yes</label>

        <input type="radio" name="poll" id="no" value="No">
          <label for="no">No</label>
        <br>
        <input type="submit" value="Vote" class="btn"> 
        </form>

      </v-layout>
    </v-slide-y-transition>
  
  </v-app>
</template>

<script>
    
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
