<template>
    <div>
           
    
         <h1 class="text -3x1 font-bold mx-10 my-10 text-orange-400">
        catalogo
         </h1>
         <p> Detalle del articulo {{ id }}</p>
    </div>
    
        
</template>

<script setup>
    const { id } = useRoute().params
</script>