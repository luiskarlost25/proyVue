
<template>
  <h1>M segundo hola mundo en VUE</h1>
  <h4>te amo claudita cavero </h4>
  <p>{{ contador }}</p>
  <button @click="incrementar"> Incrementar</button>
  <br>
  <button @click="decrementar"> Decrementar</button>

</template>

<script setup>
import {ref} from 'vue';
const contador=ref (0);

const incrementar =()=>{
  contador.value++;

}

const decrementar =()=>{
  contador.value--;

}
</script>

<style scoped>
p{
  color: red;
  font-size: 22px;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

</style>
