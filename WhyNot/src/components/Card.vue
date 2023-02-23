<script setup>
const props = defineProps({
  id: {
    type: Number,
    default: null,
  },
  url: {
    type: String,
    default: null,
  },
  name: {
    type: String,
    default: null,
  },

});

</script>
<template>
  <li>
    <figure>
      <img src="../assets/ordenador.jpg" alt="name">
    </figure>
    <div class="contentPokemon">
      <p><strong>FACTORIA F5</strong></p>
      <h3>Gijón</h3>
      <p><strong>Busco Fullstack</strong></p>
    </div>
  </li>
</template>


<style scoped>
li {
  min-width: 50px;
  border: 5px solid #73CDD2;
  border-radius: 10px;
  overflow: hidden;
}

figure {
  width: 75%;
  position: relative;
}

img {
  width: 100%;
}

h3 {
  font-size: 16px;
  color: #ffffff;
  text-transform: uppercase;
 
}

h2 {
  font-size: 16px;
  color: #000000;
  text-transform: uppercase;
  margin-bottom: 4px;
  margin-top: -24px;
  margin-right: 25px;
}





p {
  color: black;
  font-family: "Roboto";
  font-size: larger;
}





.contentPokemon {
  position: relative;
  padding: 20px;
  background-color: none;

}






@media (max-width:500px) {
  li {
    border: none;
    border-radius: 0;
    margin-bottom: 50px;
  }
}
</style>