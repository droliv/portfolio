<template>
  <div class="body">
    <Main />
    <Services />
    <Projects />
    <Tecnologies />
  </div>
</template>

<script>
import Main from './MainInfo'
import Services from './Services'
import Tecnologies from './Tecnologies'
import Projects from './Projects'

export default {
  name: 'HelloWorld',
  components: {
    Main,
    Services,
    Tecnologies,
    Projects
  },
  data () {
    return {

    }
  }
}
</script>

<style>
.body{
  margin-left: 0;
  margin-right: 0;
}
</style>
