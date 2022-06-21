<template>
   <img :src="avatar" :alt="descricao">
</template>
<script>
export default{
    name:'Picture',
    data(){
        return{
            avatar:"/img/logo.png",
            descricao: 'Essa e a nossa imagem da nosssa logo do sistema'
        }
        
    }
}
</script>
