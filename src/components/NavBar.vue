<template>
  <div class="menu">
    <b-navbar toggleable="lg" type="light" variant="light">
      <b-navbar-brand href="/"><img src="~../assets/img/drolive-min.png" alt style="width: 180px"></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <a href="#services">O que eu faço</a>
          <a href="#projects">Meus Projetos</a>
          <a href="#tecnologies">Tecnologias que utilizo</a>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style>
.menu{
  color:#a3145b;
}
.menu a {
  color:#a3145b;
  text-decoration: none;
  font-family: 'Yanone Kaffeesatz', sans-serif;
  font-size: 25px;
  margin-left: 10px;
  margin-right: 10px;
}
.menu a:hover{
   color:#a3145b;
   text-decoration-color: #45c667;
}
</style>