<template>
    <div>
      <h2>Essa é uma Descrição da Pessoa chamada {{nome}}</h2>
      <p>Estou trabalhando no momento</p>
      <p>Sou fruente nas Seguintes tecnologias</p>
      <Info/>
    
    </div>
</template>

<script>
import Info from './Info.vue'
export default {
    name: "Pessoa",
    data() {
        return {
            nome: "Mario de Sousa Junior"
        };
    },
    components: { 
        Info 
    }
}
</script>