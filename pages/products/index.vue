<template>
   
       
    <div>
        <h1 class="text-3x2 font-bold mx-10 my-10 text bg-red-400">
        </h1>
    <div class="grid grid-cols-4 gap-5 mx-10">   
        <div v-for="p in products"> 
        <NuxtLink :to="`/products/${p.id}`">{{ p.title }}></NuxtLink>
    </div> 
    </div>
    </div>

    



</template> 
<script setup>
definePageMeta({
    layout: "productos"
})

const { data: products } = await useFetch('https://fakestoreapi.com/products');
</script>

