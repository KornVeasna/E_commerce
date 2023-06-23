<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheNavbarPage from './Navbar.vue'
import TheBodyPage from './Bodypage.vue'
import TheFooterPage from './Footerpage.vue'
</script>
<template>
    <div class="wrapper-container">
        <div class="container">
            <TheNavbarPage/>
            <TheBodyPage/>
            <TheFooterPage/>
        </div>
       
    </div>
</template>
<style>

</style>