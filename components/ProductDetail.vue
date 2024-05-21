<template>
    <div> class="grid grid-cols-2">
<img :src="product.image" alt=""> 
    </div>
    <div>
        <h2>{{  product.title }}</h2> 
        <p>{{ product.price }}</p>
        <h3>{{ product.description }}</h3> 
    </div>
</template>


<script setup>
const { product} =definePromps([`Product`])

</script>

<style scoped>

</style>