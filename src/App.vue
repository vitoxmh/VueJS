<script setup>

import {ref} from 'vue'
const textHolaMundo = "Hola Mundo";

let count = ref(0);

const sumar = () => {

  count.value++;

}


const restar = () => {

  count.value--;

}


const reset = () => {

  count.value = 0;

}

</script>

<template>
  <h1>{{ textHolaMundo }} {{ count }}</h1>
  <button @click="sumar">Sumar</button>
  <button @click="restar">restar</button>
  <button @click="reset">Rese</button>
</template>

<style scoped>
</style>
