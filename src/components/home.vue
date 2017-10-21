<template>
  <div>
    <h2>Home</h2>
    <input type="text" placeholder="Introducir tarea" v-model="TextoNuevo">
    <input type="button" value="Enviar texto" v-on:click="cambiarTexto">
    <h2>{{tarea}}</h2>

  </div>
</template>

<script>
export default{
data(){
    return{
      TextoNuevo:null,
      tarea:null
    }
  },
  methods:{
    cambiarTexto(){
      this.tarea=this.TextoNuevo;
    },
},
}
</script>


<style>
</style>
