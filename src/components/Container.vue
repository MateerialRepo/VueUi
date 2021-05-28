<template>
  <div class="flex flexrow p-20">
      <div class="w-50">
        <LeftSide />
      </div>

      <div class="w-50">
        <Login />
      </div>
      
  </div>
</template>

<script>
import LeftSide from './LeftSide.vue'
import Login from './Login.vue'
export default {
    name: 'Container',
    components:{
        LeftSide,
        Login
    }
}
</script>

<style>

</style>