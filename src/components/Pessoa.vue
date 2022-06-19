<template>
    <div>
      <h2>Essa é uma Descrição da Pessoa chamada {{nome}}</h2>
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