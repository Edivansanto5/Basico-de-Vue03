<template>
  <div>
    <h1>Olá mundo</h1>
    <PrimeiroComponenteVue />
  </div>
</template>

<script>
import PrimeiroComponenteVue from './components/PrimeiroComponente.vue';
export default {
    name: "App",
    components: { 
      PrimeiroComponenteVue 
    }
}
</script>