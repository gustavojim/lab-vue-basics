<template>
  <div class="{color: colorChange, otraClasse: true}">Iteracion 5</div>
  <button @click= "onClick">Click</button>


  <div :style="{ backgroundColor: valorInput}"></div>
 <input type="color" v-model="valorInput" />
 {{color}}
</template>

<script setup>

import { ref } from 'vue';

const colorChange = ref(false);
const valorInput = ref('#fff');

const onClick = () => {

    colorChange.value = !colorChange.value

}

</script>

<style scoped>
.color {
    background-color:gold
}

</style>