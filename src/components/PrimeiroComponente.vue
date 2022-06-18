<template>
    <div>
         <h1>Olá vue</h1>
         <p>Meu nome e {{nome}} e tenho {{idade}}</p>
         <LifecyclehooksVue/>
         
    </div>
   
</template>

<script>
import LifecyclehooksVue from './Lifecyclehooks.vue'

export default {
    name: "PrimeiroComponente",
    data() {
        return {
            nome: "Edivan dos santos",
            idade: 28
        };
    },
    components: { LifecyclehooksVue }
}
</script>