<template>
  <div>
     
    <PrimeiroComponenteVue />
    <Lifecyclehooks/>
    <Picture/>
    <Pessoa/>
    <Diretivas/>
    <Info/>
  

  </div>
</template>

<script>
import PrimeiroComponenteVue from './components/PrimeiroComponente.vue';
import Lifecyclehooks from './components/Lifecyclehooks.vue';
import Pessoa from './components/Pessoa.vue'
import Diretivas from './components/Diretivas.vue';
import Info from './components/Info.vue';
import Picture from './components/Picture.vue';

export default {
    name: "App",
    components: {
    PrimeiroComponenteVue,
    Lifecyclehooks,
    Pessoa,
    Diretivas,
    Info,
    Picture
  }
}
</script>

<style>
body{
  background-color:#333;
  color: #fff;
  text-align: center;
}

</style>