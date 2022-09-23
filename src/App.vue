<template>
  <div>
    <h1>Directivas</h1>
    <hr/>
    <h2>v.text</h2>
    <span v-text="'Hola desde la directiva v-text'"></span>
    <span>{{}}</span>  <!--Transmutacion de texto-->
    <br>
    <span>Hola desde la directiva v-text</span>
    <br>
    <span v-text="titulo"></span>

    <br> Esta es una Transmutacion de texto con una variable prop
    <br>
    {{titulo}}
  </div>
</template>

<script>
  export default{
    data: () => ({
      titulo: "Hola desde Vue.js",
    }),
  }
</script>


<style scoped>
  div {
    text-align: center;
    margin: 0px 2rem;
  }
</style>