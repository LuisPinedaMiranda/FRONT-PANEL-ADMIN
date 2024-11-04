<script>
import { RouterLink, RouterView } from 'vue-router'
import Sidebar from './components/Sidebar.vue'


export default{
  data() {
    return {
      
    }
  },
  components:{
    Sidebar,
  
  }
}

</script>

<template>
 <!--    <Sidebar/> -->
  <RouterView/>
</template>

<style scoped>
a{
  color: #6e84a3 !important;
}
</style>
