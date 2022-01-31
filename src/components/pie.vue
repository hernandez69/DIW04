<template>
<footer>
    <div id="pie">
            <div class="final"><img class="envio2" src="../assets/foto13.png" alt="envio" copyright="cc-0 informacionUsuario"/></div> 
        <div id="menu1">            
            <nav>
                <ul>                    
                    <a href="#">Env&iacute;os &nbsp;</a><div class="guion">-&nbsp;</div>
                    <a href="#"> M&eacute;todos de pago &nbsp;</a><div class="guion">-&nbsp;</div>
                    <a href="#"> Estudiantes &nbsp;</a><div class="guion">-&nbsp;</div>
                    <a href="#"> Garant&iacute;a &nbsp;</a><div class="guion">-&nbsp;</div>
                    <a href="#"> Condiciones &nbsp;</a><div class="guion">-&nbsp;</div>
                    <a href="#"> Privacidad &nbsp;</a><div class="guion">-&nbsp;</div>
                    <a href="#"> Afiliados &nbsp;</a><div class="guion">-&nbsp;</div>
                    <a href="#"> Contacto &nbsp;</a>
                </ul>
            </nav>            
        </div> 
        <div class="elemento">        
            <p>© Copyright 2021 - Todos los derechos reservados - <span style="color:rgb(255, 20, 20)">Not<span style="color:rgb(118, 255, 55)">PrePared</span></span></p>
            <nav>                
                <ul>                        
            <a class="tipo5" href="#"><img src="https://img.icons8.com/color/50/000000/instagram-new--v1.png" height="25px"/></a>
            <a class="tipo5" href="#"><img src="https://img.icons8.com/color/48/000000/facebook-circled--v4.png" height="25px"/></a>
            <a class="tipo5" href="#"><img src="https://img.icons8.com/fluency/48/000000/youtube-play.png" height="25px"/></a>
            <a class="tipo5" href="#"><img src="https://img.icons8.com/fluency/48/000000/twitter.png" height="25px"/></a>
                </ul>
            </nav>             
        </div>
    </div>
</footer>    
</template>

<script>
export default {

}
</script>

<style scoped>

#pie 
{
    background-color: #030303;
}

#pie p 
{
    color: white;
    text-align: center; 
}

#menu1
{    
    justify-content: center;
    display: flex;
    font-weight:900;
    text-align: center;  
}

#menu1 nav ul
{
    display: flex;
    justify-content: center;
    text-decoration: none;
}

#menu1 nav ul a
{
    text-decoration: none;
    color:white;    
}

#menu1 nav ul a:hover
{
    color:red;
}

.guion
{
    color: crimson;
}

.elemento
{
    justify-content: space-around;
    align-items: center;
    display: flex;
    margin:0 0 0 1em;
    padding: 0.5em;
    margin-left: 35em;
}

.tipo5
{
    background-color: #000000;
    padding: 0.3em;
    margin:0 0 0 1em;
    align-items: center;
    justify-content: right;
}

.tipo5 a
{
    text-decoration: none;
    color:black;
}
</style>