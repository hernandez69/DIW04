<template>
  <div class="bloque2">
      <div id="producto-datos">
      <h1>Samsung UE55TU7000 58" Crystal UHD 4K HDR10</h1>
      <h2>478.99€ <span class="iva">sin IVA: 395,86€</span></h2>
      <h3><span class="envio">¡¡ENVÍO GRATIS!!</span></h3>
      <h4>Disponibilidad :<span class="disponibilidad"> ¡EN STOCK!  ¡REC&Iacute;BELO MAÑANA!</span></h4>
          <div class="wrapper">
              <button class="btn" @click="cambiarContador('-1')" type="button" name="button">-</button>
              <input class="cantidad" type="text" name="name" :value="contador">
              <button class="btn" @click="cambiarContador('1')" type="button" name="button">+</button>
              <button class="boton"><span class="material-icons"></span> AÑADIR CARRITO</button>
          </div>  
      </div>  
  </div>
</template>

<script>
export default {    
      Name: 'ProductoDatos',
    data () {
        return {
            contador: 1
        }
    },
    methods: {
        cambiarContador(num) {
            this.contador += +num;
            if (!isNaN(this.contador) && (this.contador < 0)) {
              this.contador = 0
            }
        }
    },    
}
</script>

<style scoped>

.bloque2
{    
  margin-top: 3rem;
}

#producto-datos 
{
  flex: 1 1 18rem;
}

h1
{
  font-size: 2.2rem;
}

h2
{
  font-size:1.7rem;
  color: #fd0000;
}

h3
{
  color:rgb(2, 175, 25);
}

span.iva 
{
  font-size:1rem;
  font-weight: normal;
  color: #000000
}

.wrapper 
{
  height: 2rem;
  display: flex;
}

.cantidad 
{
  border: none;
  text-align: center;
  width: 2rem;
  font-size: 1.2rem;
  border: 1px solid #d8d8d8;
}

.btn 
{
  border: 1px solid #d8d8d8;
  width: 1.8rem;
}

button:focus, input:focus 
{
  outline: 0;
}

.boton
{
  height: 2rem;
  width: 20%;
  margin-left: 25px;    
}

.final
{
  justify-content: left;
  display: flex;
}

.diferencia h1
{
  color:rgb(2, 175, 25);
  font-size: 1rem;    
}

.disponibilidad
{
  color: #fd0000;
}
</style>