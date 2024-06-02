<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
     <div class="bloco">
     <p class="principal">
      Aniely Soares é uma talentosa profissional que combina duas paixões em sua carreira: design de sobrancelhas e fotografia. Com um olhar apurado para a estética e a beleza, Aniely dedica-se a realçar a expressão natural de cada cliente através de técnicas avançadas de design de sobrancelhas. Seu trabalho minucioso e personalizado garante resultados que valorizam os traços únicos de cada rosto.
      Além de sua habilidade como designer de sobrancelhas, Aniely também se destaca na fotografia. Seu talento para capturar momentos e emoções se reflete em suas fotos, que transmitem autenticidade e beleza. Com um portfólio diversificado, Aniely sabe como iluminar a essência de seus modelos e criar imagens impactantes.
      Combinando precisão técnica e uma sensibilidade artística única, Aniely Soares é uma profissional dedicada a transformar e capturar a beleza em todas as suas formas.
      </p>
     <h3>Minhas redes sociais</h3>
    <ul>
      <li><a href="https://www.instagram.com/anielysoaress/" target="_blank" rel="noopener">Instagram</a></li>
      <li><a href="https://wa.me/66992525061" target="_blank" rel="noopener">WhatsApp</a></li>
      <li><a href="https://www.google.com/maps/place/Aniely+Soares+-+Photography+%26+Beauty/@-9.9118237,-59.9722333,9z/data=!4m6!3m5!1s0x93b3c1fc915c82c9:0xc927b67a65d21823!8m2!3d-10.1870744!4d-59.4317253!16s%2Fg%2F11l6thfwp2?entry=ttu" target="_blank" rel="noopener">Localização</a></li>
    </ul>
    <h3>Conheça meu trabalho!</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Sobrancelha</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Fotografia</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Social Media</a></li>
      </ul>
    <h3>Agendas abertas</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">Junho a Dezembro de 2024</a></li>
    </ul>
  </div>
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
  margin: 30px 0 0;
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
p {
  text-align: justify
  
  }

  div.bloco {
  height: 425px;
  border: 5px solid #000000;
  border-radius: 28px;
  margin: 5px; }
  p.principal {
    text-align: justify;
    margin: 20px;

  }
  
</style>
