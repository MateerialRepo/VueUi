<template>
    <div>
        <h1 class="invisible sm:visible font-bold">Welcome to <span class="text-blue-600">Vetsark</span></h1>
        <h1 class="text-left visible sm:invisible font-bold">Hey</h1>
        
        <p class="mt-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore. </p>

        <LoginForm />
    </div>
    
</template>

<script>
import LoginForm from './LoginForm.vue'

export default {
    name: 'Login',
    components: {
        LoginForm,
    },
}
</script>

<style>

</style>