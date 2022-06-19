<template>
    <h2 v-if="mostrar">Meu sonho e ser grande</h2>
    <p>Estou trabalhando no momento</p>
    <p>Sou fruente nas Seguintes tecnologias</p>
    <ul>
        <li>RUBI</li>
        <p>PHP</p>
        <p>PYTHON</p>
        <p>HTML5</p>
        <P>CSS5</P>
        <P>JAVACRIPT</P>
    </ul>
    <P>Uso Alguns FrameWork:</P>
    <ul>
        <li>React Native</li>
        <li>React</li>
        <li>Vue02</li>
        <li>Vue03</li>
        <li>node js</li>
        <li>Flant</li>
    </ul>
   
</template>

<script>
export default {
    name:'Info',
    data(){
        return{
            mostrar:true
        }
    }
}
</script>
