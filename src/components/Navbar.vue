<template>
    <nav class="h-20 pt-10 font-Poppins text-white bg-[#0E77FF]">
       <ul class="flex justify-around items-center">
        <li class="text-lg">Logo</li>
        <li>
            <ul class="flex gap-10 justify-center items-center">
                <li class="cursor-pointer">About</li>
                <li class="cursor-pointer">Services</li>
                <li class="cursor-pointer">Case Studies</li>
                <li class="cursor-pointer">Testimonials</li>
                <li class="cursor-pointer">Contact</li>
                <router-link to="/login" class="px-12 py-3 bg-white text-black font-bold rounded-md">Login</router-link>
                <!-- <button class="px-12 py-3 bg-white text-black font-bold rounded-md">Login</button> -->
            </ul>
        </li>
       </ul>
    </nav>
</template>

<script setup>

</script>
