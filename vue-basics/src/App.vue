<template>

<Navbar/>
    <div>
        {{2 + 2}}
    </div>
    <div>      
        {{holaMundo()}}
    </div>
<Footer/>
<Iteracion3/>
<Iteracion4/>
<Iteracion5/> 
<IteracionFormulario></IteracionFormulario>
</template>

<script setup>

import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
// import Iteracion3 from './components/Iteracion3.vue';
import Iteracion4 from './components/Iteracion4.vue';
import Iteracion5 from './components/Iteracion5.vue';
import IteracionFormulario from './components/IteracionFormulario.vue';

const holaMundo = () => {
    return 'Hola mundo'
};


</script>

<style scoped>
</style>