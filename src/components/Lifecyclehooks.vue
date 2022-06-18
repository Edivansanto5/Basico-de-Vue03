<template>
    <div>
        <h1>Meu nome e {{nome}}</h1>
    </div>
</template>

<script>
export default {
    name:'Lifecyclhooks',
    data(){
        return{
            nome: 'Edivan santos'
        }
    },
    created(){
      setTimeout(()=>{
          this.nome =  'Marcos de Abrel'
      },1000)
      setTimeout(()=>{
        this.nome = 'Elenildo Sousa'
      },3000)
       setTimeout(()=>{
            this.nome = 'Edlison santos'
        },5000) 
    },
    mounted(){
        setTimeout(()=>{
            this.nome = 'Fabio de sousa'
        },7000)
       
    }
}
</script>