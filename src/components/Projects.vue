<template>
  <section id="projects" class="container-fluid padding">
    <h2>Meus Projetos</h2>
    <div class="row project">
      <div class="col-lg-3 col-md-6 col-sm-12">
        <div class="card" style="width: 100%;">
          <div class="card-header">Code Solidário</div>
          <img class="card-img-top" src="~../assets/img/code-min-compressed.jpg" alt="Card image cap" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
#projects {
  margin-bottom: 30px;
}
.card:hover {
  -webkit-box-shadow: 0px 4px 27px -6px rgba(0, 0, 0, 1);
  -moz-box-shadow: 0px 4px 27px -6px rgba(0, 0, 0, 1);
  box-shadow: 0px 4px 27px -6px rgba(0, 0, 0, 1);
}
.card {
  text-align: center;
  align-content: center;
  align-items: center;
  margin: 0 auto;
  margin-top: 20px;
  border: 5px solid #a3145b !important;
}
.card-header {
  width: 100%;
  background-color: #a3145b !important;
  color: #f9f9f9;
}
.card a {
  color: #45c667;
}
.card a:hover {
  color: #45c667;
  text-decoration: none;
}
</style>