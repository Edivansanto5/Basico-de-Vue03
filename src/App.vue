<template>
  <div>
    <PrimeiroComponenteVue />
    <Lifecyclehooks/>
    <Pessoa/>

  </div>
</template>

<script>
import PrimeiroComponenteVue from './components/PrimeiroComponente.vue';
import Lifecyclehooks from './components/Lifecyclehooks.vue';
import Pessoa from './components/Pessoa.vue'

export default {
    name: "App",
    components: { 
      PrimeiroComponenteVue,
      Lifecyclehooks,
      Pessoa
    }
}
</script>