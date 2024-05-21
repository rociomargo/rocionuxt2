<template>
    <div class="ms-10 ,y-10 text-4x1 font-thin text-red-600">
            <NuxtLink to="/"> LaTiendecita</NuxtLink>
    </div>
    <slot />
    <div class="mx-10 my-10 pt-5 flex gap-5 font-bold shadow-inner">
         <button><NuxtLink to="/">Home</NuxtLink></button>
         <button><NuxtLink to="/about">About</NuxtLink></button>
         <button><NuxtLink to="/products">Products</NuxtLink></button>
    </div>
</template>

<script setup>
</script>