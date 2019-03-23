<template>
  <v-app>
    <NavBar></NavBar>
    <Presentation></Presentation>
    <Proyects></Proyects>
    
  </v-app>
</template>

<script>
//import HelloWorld from './components/HelloWorld'
import NavBar from './components/NavBar'
import Presentation from './components/Presentation'
import Proyects from './components/Proyects'

export default {
  name: 'App',
  components: {
    //HelloWorld,
    NavBar,
    Presentation,
    Proyects
  },
  data () {
    return {
      //
    }
  }
}
</script>
<style>
body,html{
  height: 100%;

}
.container{
  height:100%;
  width:100%;
}
</style>

