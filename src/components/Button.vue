<template>
  <button type="{{buttonType}}" class="bg-blue-400 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Login</button>
</template>

<script>

export default {
    name: 'Button',
    props: {
        buttonType: String,
    }
}

</script>

<style scoped>

</style>