<template>
  <div class="menu container-fluid" style="background-color: #f9f9f9">
    <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #f9f9f9">
  <a class="navbar-brand" href="#"><img src="~../assets/img/drolive-min.png" alt style="width: 180px"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">O que eu faço <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Meus projetos</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Minhas habilidades</a>
      </li>
    </ul>
  </div>
</nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
.menu {
  color: #a3145b;
  width: 100% !important;
}
.menu a {
  color: #a3145b !important;
  text-decoration: none;
  font-family: "Yanone Kaffeesatz", sans-serif;
  font-size: 25px;
  margin-left: 10px;
  margin-right: 10px;
}
.menu a:hover {
  color: #a3145b !important;
  text-decoration-color: #45c667;
}
ul {
  margin-left: 20px;
}
</style>