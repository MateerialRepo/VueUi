<template>
  <form class="form">
      <label>Email</label>
      <input type="email" class="form-input block ">
      <input type="password" placeholder="password">
      <div class="flex flex-row justify-between">
        <Button
        buttonType = "submit"
       />

       <a href="" class="hover:underline text-blue-600"><p>forgot password?</p></a>
      </div>
      

  </form>
</template>

<script>
import Button from './Button.vue'

export default {
    name: 'LoginForm',
    components:{
        Button,
    }

}
</script>

<style>

</style>