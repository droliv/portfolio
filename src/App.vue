<template>
   <div id="app" class="container-fluid" style="margin: 0;">
    <NavBar />
    <router-view/>
   <Footer />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "./components/NavBar";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    HelloWorld,
    NavBar,
    Footer
  },
  data() {
    return {};
  },
  methods: {}
};
</script>

<style>
@import 'bootstrap/dist/css/bootstrap.min.css';

h1 {
  font-family: "Yanone Kaffeesatz", "Helvetica Neue", Arial, sans-serif;
  font-size: 60px !important;
  text-align: center;
}
h2 {
  font-family: "Yanone Kaffeesatz", "Helvetica Neue", Arial, sans-serif;
  font-size: 50px !important;
  text-align: center !important;
  color: #a3145b;
  padding-top: 20px;
  padding-bottom: 20px;
  text-transform: uppercase;
}
#app {
  position: relative;
  margin-left: 0;
  margin-right: 0;
}
.padding {
  padding-bottom: 20px;
  padding-top: 20px;
}
p {
  font-family: "Helvetica Neue" "Helvetica", "Arial", sans-serif;
}
</style>
