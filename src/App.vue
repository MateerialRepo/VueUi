<template>
  <div class="container">
    <Container />
  </div>
</template>

<script>
import Container from './components/Container.vue'

export default{
  name: 'App',
  components:{
    Container,
  }
  
}
</script>

<style>
#app {
  font-family: Poppins, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
