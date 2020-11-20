<template>
  <div class="main-container">     
    <navbar/>
    <Nuxt/>
    <footer>
      <foot/>
    </footer>
    
  </div>  
</template>

<script>
import navbar from '../components/navbar'
import foot from '../components/foot'
export default {
  components:{
    navbar,
    foot
  }
}
</script>

<style>
.main-container{
  padding: 1%;
  background-color: #222831;
}

</style>
