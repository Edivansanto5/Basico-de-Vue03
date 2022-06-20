<template>
    <h4 v-if="mostrar">Estou trabalhando no momento</h4>
    <p v-else>Sou um programador iniciante</p>
    <p>Sou fruente nas Seguintes tecnologias</p>
    <p>ola v-show</p>
    <ul>
        <li> <a v-bind:href="rubi">RUBI</a></li>
        <li> <a :href="php"> PHP </a></li>
        <li> <a :href="pithon"> PYTHON </a></li>
        <li> <a :href="html"> HTML5 </a></li>
        <li> <a :href="css"> CSS5 </a></li>
        <li> <a :href="js">JAVACRIPT </a> </li>
    </ul>
    <P >Uso Alguns FrameWork:</P>
    <ul v-show="mostrarFrameWork">
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
            mostrarTecnologia: true,
            rubi: 'https://www.jruby.org/',
            php:'https://www.php.net/',
            pithon:'https://www.python.org/',
            html:'https://www.w3schools.com/html/',
            css:'https://www.w3schools.com/css/',
            js:'https://www.w3schools.com/js/',
            mostrar:false,
            mostrarFrameWork:true,
        }
    }
}
</script>