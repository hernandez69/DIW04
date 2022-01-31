<template>
  <section id="producto-imagen">
      <div class="img-big"> 
          <img v-bind:src="fotos[0]" alt="TV Samsung">
      </div>
        <div class="img-mini">
          <a @click="cambiarFoto(1)"><img  v-bind:src="fotos[1]" alt="TV Samsung" copyright="cc-0 imagenTVSamsung"></a>
          <a @click="cambiarFoto(2)"><img  v-bind:src="fotos[2]" alt="TV Samsung" copyright="cc-0 imagenTVSamsung"></a>
          <a @click="cambiarFoto(3)"><img  v-bind:src="fotos[3]" alt="TV Samsung" copyright="cc-0 imagenTVSamsung"></a>
          <a @click="cambiarFoto(4)"><img  v-bind:src="fotos[4]" alt="TV Samsung" copyright="cc-0 imagenTVSamsung"></a>
        </div>
      </section>    
</template>

<script>
export default {
    Name: 'ProductoImagen',
    data () {
        return {
            fotos: [
                require ('../assets/e1.jpg'),
                require ('../assets/e1.jpg'),
                require ('../assets/e2.jpg'),
                require ('../assets/e3.jpg'),
                require ('../assets/e4.jpg')]
        }
    },
    methods: {
        cambiarFoto(id) {
            this.fotos[0] = this.fotos[id]
        }
    }
}
</script>

<style scoped>

#producto-imagen 
{
    padding: 1rem;
    margin: 1rem;
    margin-top: 1rem;
}

.img-mini
{
    display: flex;
    align-items: center;
    margin-left: 3em;
    flex-direction: row;
    justify-content: space-around;
}

.img-mini img 
{
    width: 130px;
    height: 130px;
    border:2px solid #d8d8d8;
    display: flex;
    align-items: center;
}    

</style>