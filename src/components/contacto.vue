<template>
<div  id='contact1'>
  <h2>Contacto</h2>
  <ul>
    <li v-for= "contacto in contactos">{{contacto}}</li>
    </ul>

</div>
</template>

<script>
export default{
data(){
  return {contactos:[
    '',
    'Elma Marcela Rico'
  ]}
}}

</script>

<style>
</style>
