<template>
<header class="header">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Material+Icons+Outlined">
    <div class="logo-buscador">
        <div class="contenedor">
            <img src="../assets/foto1.jpg" alt="logotipo" copyright="cc-0 sharigan" />
            <div id="NOT"><h1><span style="color:rgb(255, 20, 20)">Not<span style="color:rgb(118, 255, 55)">PrePared</span></span></h1></div>  
        </div>        
  
        <div class="" id="buscador"><input type="text" placeholder="Buscar en tienda NotPrePared ... "><button class="buscar">Buscar</button></div>
        <div class="login">
            <div class="boton2"><a href="#"><img class="tip1" src="../assets/foto11.jpg" alt="register" copyright="cc-0 direccion" />REGISTRO </a></div>
            <div class="boton2"><a href="#"><img class="tip2" src="../assets/foto3.png" alt="sesion" copyright="cc-0 spaceinvaders" />INICIO SESI&Oacute;N</a></div>
            <nav>
                <ul>
            <a href="#"><span class="material-icons-outlined icon">add_shopping_cart</span></a>
                </ul>
            </nav>            
        </div>
    </div>         
    <div id="MENU">
        <div class="menuprincipal">
            <nav>
                <ul>
                    <a href="#">INICIO</a>
                    <a href="#">ORDENADORES</a>
                    <a href="#">TV</a>
                    <a href="#">MÓVILES</a>
                    <a href="#">TABLETS</a>
                    <a href="#">MULTIMEDIA</a>
                </ul>
            </nav>
        </div>
    </div>
</header>
</template>

<script>
export default {

}
</script>

<style scoped>

.contenedor
{
    display: flex;
    margin-left: 25px;
}

.logo-buscador
{
    display: flex;  
    justify-content: space-around;
    align-items: center;
    font-size: 1.5rem;
}

.boton2
{
    background-color: white;
    padding: 0.5em;
    margin:0 0 0 1em;
    align-items: center;
}

.boton2 a
{
    text-decoration: none;
    color:black;
    font-size: 20px;
    padding: 0.9em;
}

.boton2:hover
{
    background-color: grey;
    border-radius: 10px;    
}

.tip1
{
    margin-right: 1rem;
}

.tip2
{
    margin-right: 1rem;
}

#MENU
{    
    background: #000000;
    z-index:999;
    padding:0.5rem;
    text-decoration: none;
}

.menuprincipal nav ul
{
    display: flex;
    justify-content: space-around;    
    font-weight: 800;
}

.menuprincipal nav ul a
{
    text-decoration: none;
    color:white;
}

.menuprincipal nav ul a:hover
{
    color:red;
}

.login 
{  
    text-decoration: none;
    color:black;
    font-weight: 700;
    display: flex;
    align-items: center;
}

.login img
{
    width: 30px;
}

#buscador
{
    margin-left: 4.5em;
}

#buscador>input
{
    width: 450px;
    height: 35px;
}

.buscar
{
    height: 41px;
}
#NOT
{
    margin: 0;
}

.icon
{
    font-size: 3rem;

}
</style>