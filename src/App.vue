<template>
  <h1> Hello {{ name}} </h1>
  <div v-text="msg"></div>

</template>

<script>

export default {
  name: 'App',
  data(){
    return {
      name: "Dhrubo",
      msg: "Have a nice day sir"
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
