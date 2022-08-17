<template>
    <div>
        <ul>
            <li><a href="#" target="_blank">Home</a></li>
            <li><a href="#" target="_blank">Projetos</a></li>
            <li><a href="#" target="_blank">Contatos</a></li>
            
        </ul>
    </div>
</template>

<script>
export default {
    name:'Header',
}
</script>

<style scoped>
    ul{
        list-style: none;
        display: flex;
        background-color: #111;
    }
    li{
        margin-right: 12px;
    }
    a{
        color:#DDD;
        text-decoration: none;
        transition: .5s;
    }
    a:hover{
        color: turquoise;
    }
</style>