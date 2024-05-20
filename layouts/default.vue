<template>
    <div>
        <header class="flex justify-between mx-10 my-10">
            <div>
                Logo
            </div>
            <div class="flex gap-8">
                <button class="bg-pink-300 px-4 py-2 rounded-2xl">Home</button>
                <button class="bg-pink-300 px-4 py-2 rounded-2xl">About</button>
                <button class="bg-pink-300 px-4 py-2 rounded-2xl">Products</button>
            </div>
        </header>
    </div>
    <div> 
        
        <div class="mx-10 my-10 flex gap-7 ">
        <button class="font-bold"> <NuxtLink to="/" home ></NuxtLink></button>
        <button class="font-bold"> <NuxtLink to="/about" about ></NuxtLink></button>
        <button class="font-bold"> <NuxtLink to="/products" products ></NuxtLink></button> 

        </div>
    </div>

<div>
    
    <slot/>
</div>
</template>

<script setup>
</script>