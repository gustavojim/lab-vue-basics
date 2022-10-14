<template>

<Navbar/>
    <div>
        {{2 + 2}}
    </div>
    <div>      
        {{holaMundo()}}
    </div>
<Footer/>

</template>

<script setup>

import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'

const holaMundo = () => {
    return 'Hola mundo'
}

</script>

<style scoped>
</style>