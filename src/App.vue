<template>
  <div>
    <PrimeiroComponenteVue />
    <Lifecyclehooks/>
  </div>
</template>

<script>
import PrimeiroComponenteVue from './components/PrimeiroComponente.vue';
import Lifecyclehooks from './components/Lifecyclehooks.vue';
export default {
    name: "App",
    components: { 
      PrimeiroComponenteVue,
      Lifecyclehooks 
    }
}
</script>