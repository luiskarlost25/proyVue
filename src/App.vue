
<template>
  <h1>M segundo hola mundo en VUE</h1>
  <h4>te amo claudita  </h4>
  <p>{{ contador }}</p>
  <button @click="incrementar"> Incrementar</button>
  <br>
  <button @click="decrementar"> Decrementar</button>

</template>

<script setup>
    import Contador from './components/Contador.vue';


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
