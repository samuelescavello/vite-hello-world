<template>
  <AppTitle />
  <AppJambo />
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppJambo from './components/AppJambo.vue';
  export default {
    name:'App',
    components:{
      AppTitle,AppJambo
    },
    data(){
      return{
        
      }
      
    }
  }
</script>

<style scoped>

</style>