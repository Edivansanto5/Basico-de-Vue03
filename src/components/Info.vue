<template>
    <h4 v-if="mostrar">Estou trabalhando no momento</h4>
    <p v-else>Sou um programador iniciante</p>
    <p>Sou fruente nas Seguintes tecnologias</p>
    <div>
        <button @click="exibirEmail">MostrarEmail</button>
    </div>
    <p v-if="mostarEmail">Mande uma mensagem para meu {{email}} </p>
    
    <p>Para acessar meu GitHub basta Clicar <a :href="aqui" target="_blank" >Aqui</a></p>
    <ul>
        <li> <a v-bind:href="rubi">RUBI</a></li>
        <li> <a :href="php"> PHP </a></li>
        <li> <a :href="pithon"> PYTHON </a></li>
        <li> <a :href="html"> HTML5 </a></li>
        <li> <a :href="css"> CSS5 </a></li>
        <li> <a :href="js">JAVACRIPT </a> </li>
    </ul>
    <Picture/>
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
import Picture from './Picture.vue'
export default {
    name:'Info',
    components:{
        Picture
    },
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
            mostarEmail: true,
            mostrarFrameWork:true,
            aqui:'https://github.com/Edivansanto5',
            email:'Edivansantos1678@gmail.com',

        }
    },
    methods:{
        exibirEmail(){
            console.log('testando o botão')
        }
    }
    }
</script>