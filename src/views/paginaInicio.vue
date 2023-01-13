<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
    </div>
    <div>
        <form action="">
            <input type="text">
            <br>
            <br>
            <input type="button" value="Ingresar" class="btn btn-primary">
        </form>
    </div>
  </template>
  
  <script>
  export default {
    name: 'paginaInicio',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  h1{
    font-size: 25px;
  }

  </style>
  