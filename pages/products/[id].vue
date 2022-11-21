<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
        Voluptates deleniti rem laboriosam aut minus officiis quibusdam eos optio! Natus, ex!</p>
    </div>
</template>

<script setup>
const { id } = useRoute().params
definePageMeta({
    layout: 'products'
})
</script>
<style scoped>

</style>