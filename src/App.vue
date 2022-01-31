<template>
  <div class="garbage">
  <cabecera/>
  <breadcrumb/>  
    <div class="seccion">
      <producto/>
      <precio/>
    </div>
  <descripcion/>
  <pie/>
  </div>  
</template>

<script>
import cabecera from './components/cabecera.vue'
import breadcrumb  from './components/breadcrumb.vue'
import producto from './components/producto.vue'
import precio from './components/precio.vue'
import pie from './components/pie.vue'
import Descripcion from './components/descripcion.vue'


export default {
  name: 'App',
  components: {
    cabecera,breadcrumb,producto,precio,pie,
    Descripcion
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

body
{
  margin:  0px;
  padding: 0px;
  box-sizing: border-box;
}

.seccion
{
  display: flex;
  flex-direction: row;
  margin: auto;
  justify-content: center;
}
</style>
