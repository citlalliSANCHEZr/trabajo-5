<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      En esta pagina podras obtener todos los enlaces a nuestras redes, para que no te pierdas de las actualizacioines.
      
    </p>
    <h3>redes</h3>
    <ul>
      <li><a href="https://instagram.com/creaciones.judith.78?utm_medium=copy_link">instagram</a></li>
      <li><a href="">Facebook</a></li>
      <li><a href="">Whatsapp</a></li>
    </ul>
    

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
