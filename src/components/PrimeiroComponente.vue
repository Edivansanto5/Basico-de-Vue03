<template>
    <div>
         <h1>Olá vue</h1>
         <p>Meu nome e {{nome}} e tenho {{idade}}</p>   
    </div>
   
</template>

<script>
export default {
    name: "PrimeiroComponente",
    data() {
        return {
            nome: "Edivan dos santos",
            idade: 28
        };
    },
    components: { 
        
    }
}
</script>