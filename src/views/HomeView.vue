<template>
  <Header/>
  <Pasteles/>
  <Wavedown/>
  <Adornos/>
  <Forms/>
  <Info/>
  <Footer/>
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/footer.vue'
import Info from '@/components/Info.vue'
import Pasteles from '@/components/Pasteles.vue'
import Adornos from '@/components/Adornos.vue'
import Wavedown from '@/components/Wavedown.vue'
import Forms from '@/components/Forms.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    Header,
    Footer,
    Info,
    Pasteles,
    Adornos,
    Wavedown,
    Forms,
  }
}
</script>
