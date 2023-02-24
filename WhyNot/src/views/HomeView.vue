<template>
<HeaderComponent></HeaderComponent>
<NavBar></NavBar>

  
  <main>
    <h3>Find the best web project for you</h3>
    <section>
      <ul>
        <Card></Card>
        <Card></Card>
        <Card></Card>
        <Card></Card>
        <Card></Card>
        <Card></Card>
        <Card></Card>
      </ul>
    </section>
  </main>
  <FooterComponent/>

</template>
<script setup>
import Card from '../components/Card.vue';
import HeaderComponent from '../components/HeaderComponent.vue';
import FooterComponent from '../components/FooterComponent.vue';
import NavBar from '../components/NavBar.vue';
</script>


<style scoped>
h3 {
  font-family: "Zen Dots", sans-serif;
  font-size: 3vw;
  margin-left: 40px;
}

section {
  padding: 30px;
  font-size: 16px;
  font-family: "Roboto", sans-serif;
}

ul {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 25px;
  list-style: none;
}

@media (max-width:900px) {
  ul {
    grid-template-columns: 1fr 1fr 1fr;
  }

}

@media (max-width:700px) {
  ul {
    grid-template-columns: 1fr 1fr;
  }

}

@media (max-width:500px) {
  h3 {
    margin-bottom: 30px;
  }
  
  ul {
    grid-template-columns: 1fr;

  }

  section {
    padding: 0;
  }

}
</style>