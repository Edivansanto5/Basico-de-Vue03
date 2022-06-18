<template>
    <div>
      <h2>Essa é uma Descrição da Pessoa chamada {{nome}}</h2>
    </div>
</template>

<script>
export default {
    name:'Pessoa',
    data(){
        return{
           nome:'Mario de Sousa Junior'
        }
    }
}
</script>