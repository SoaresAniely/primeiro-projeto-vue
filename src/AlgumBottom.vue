<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Alguns antes e depois a fim de comparação de resultados. 
      </p>
    
    <h3>Abaixo, motivos pelos quais é de suma importância a higienização das sobrancelhas.</h3>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #857768;
}
</style>
