<template>
    <div>
            <header class="flex justify-between mx-10 my-10">
            <div class="text-4x1 text-red-400">
                <NuxtLink to="/"> LaTiendecita </NuxtLink>
            </div>
            <div class="flex gap-8">
                <button class="btn"><NuxtLink to="/">Home</NuxtLink></button>
                <button class="btn"><NuxtLink to="/about">About</NuxtLink></button>
                <button class="btn"><NuxtLink to="/products">Products</NuxtLink></button>
                </div>
       
            </header>
       
        </div>
    
    <slot/>
</template>

<script setup>
</script>