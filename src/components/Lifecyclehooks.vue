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
        this.nome = 'Marcelo'
    },
    mounted(){
        this.nome = 'Fabio'
    }
}
</script>