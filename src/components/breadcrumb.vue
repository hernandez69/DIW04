<template>
  <section id="camino-migas">
      <a class="inicio" href="#"> Inicio </a> >>
      <a href="#">TV </a> >>
      <a class="actual" href="#">TV Samsung</a> 
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>

section#camino-migas 
{
    display:flex;
    margin-top: 1rem;
}
section#camino-migas a, a:hover, a:visited
{
    text-decoration: none;
    font-size: 1.4rem;
    margin-left: 1rem;
    margin-right: 1rem;
    color: #020202;
}
section#camino-migas a.actual {
    font-weight: 700;
}
section#camino-migas {
    margin-left: 1rem;
    color: #ff0000;
}
</style>