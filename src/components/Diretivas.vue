<template>
  <h3>Meu nome é {{nome}}</h3>
  <p>Meus sonho e ser um bom Progamador</p>
  <p v-if="mostrar">Para eu poder ganhar um bom dinheiro e ajudar a minha familia</p>
  <p>Em caso de desistencia eu serei um mero fracassado da populaçao brasileira</p>
</template>

<script>
    export default {
        name:'Diretivas',
        data(){
            return{
                nome:'Edivan santos ',
                mostrar:false,
            }
        }
    }
</script>

