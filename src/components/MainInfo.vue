<template>
  <section id="topo">
    <div class="row main">
      <div class="fundo">
        <div class="container">
          <img src="~../assets/img/profile_optimized.jpg" class="rounded-circle" alt />
          <h1>Daniele Oliveira</h1>
          <p>
            Desenvolvedora Full Stack com conhecimento das principais linguagens e frameworks para desenvolvimento web
            e fundadora do Code Solidário, um projeto que tem o objetivo de incentivar o desenvolvimento de projetos de interesse social.

          </p>
          <div class="icons">
            <a
              href="https://github.com/droliv"
              class="fa fa-github"
              target="_blank"
              title="Link para o github"
            ></a>
            <a
              href="https://www.linkedin.com/in/reisdaniele/"
              class="fa fa-linkedin"
              target="_blank"
              title="Link para o linkedin"
            ></a>
            <a
              href="http://api.whatsapp.com/send?1=pt_BR&phone=5547988997049"
              class="fa fa-whatsapp"
              target="_blank"
              title="Link para o whatsapp"
            ></a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.main .fundo {
  background: rgba(163, 20, 91, 0.75);
  min-width: 100%;
  min-height: 100%;
}

.main {
  background: url("~../assets/img/fundo-min-compressed.jpg") no-repeat;
  background-size: cover;
  position: relative;
}
.rounded-circle {
  width: 250px;
  height: 250px;
}
.container {
  font-size: 25px;
  text-align: center;
  color: #f9f9f9;
  margin: 0 auto;
  padding: 5%;
}
.container p {
  font-weight: bold;
}
.fa {
  padding-top: 5px;
  font-size: 40px;
  width: 50px;
  height: 50px;
  text-decoration: none;
  border-radius: 50%;
  background: #45c667;
  color: white;
  margin: 5px;
}

.fa:hover {
  opacity: 0.7;
  text-decoration: none;
  color: #f9f9f9;
}
</style>