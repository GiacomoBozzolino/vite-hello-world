<script >
import AppTitle from './components/AppTitle.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  components:{
    AppTitle,
    Jumbotron,
  }
}
</script>

<template lang="">
  <div class="container">
    <div>
      <Jumbotron/>
    </div>
    <div>
      <AppTitle/>
    </div>

  </div>
</template>



<style lang="">
  
</style>