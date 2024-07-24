<template>
 <div>
     <navigation />
     <Stater />
     <About/>
     <FooterBar />
 </div>
</template>

<script>
import navigation from './components/navigation.vue'
import FooterBar from './components/Footer.vue';
import Stater from './components/Content/Stater.vue';
import About from './components/Content/about.vue';
export default {

  name: 'App',
  components:{
    navigation,
    FooterBar,
    Stater,
    About
  }

}
</script>

<style>

</style>
