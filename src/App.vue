<template>
 <div>
     <navigation />
     <Stater />
     <FooterBar />
 </div>
</template>

<script>
import navigation from './components/navigation.vue'
import FooterBar from './components/Footer.vue';
import Stater from './components/Content/Stater.vue';
export default {

  name: 'App',
  components:{
    navigation,
    FooterBar,
    Stater
  }

}
</script>

<style>

</style>
