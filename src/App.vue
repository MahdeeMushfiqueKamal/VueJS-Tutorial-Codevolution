<template>
  <h1> Hello {{ name}} </h1>
  <div v-text="msg"></div>
  <div v-html="popup"></div>
  <h2 v-bind:id="headingID"> My Heading with binded ID</h2>
  <button v-bind:disabled="isDisabled"> Demo button </button>
</template>

<script>
export default {
  name: 'App',
  data(){
    return {
      name: "Dhrubo", msg: "Have a nice day sir", 
      popup: '<a href="#"> Click me! </a>', 
      headingID: 'myHeadingID', 
      isDisabled: false, 
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
