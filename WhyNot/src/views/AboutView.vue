<template>
  <div class="about-us">
    <div class="section">
      <h2>Nuestra empresa</h2>
      <p>Nuestro Marketplace es un proyecto innovador en el mundo de la tecnología que ha sido diseñado para conectar a creadores y emprendedores en un solo lugar. En Why Not, estamos ayudando a las personas a llevar sus ideas y proyectos al siguiente nivel.

Es una plataforma fácil de usar que permite a los creadores publicar sus proyectos , productos , ideas con los profesionales y jóvenes promesas del mundo Tech que  están deseando  un cambio.
 
Nuestro lema es "Haz tus ideas realidad"</p>
    </div>
    <div class="section">
      <h2>Nuestro equipo</h2>
      <div class="grid">
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/4a4e4d/ffffff/?text=1" alt="Miembro del equipo 1">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/1281e6/ffffff/?text=2" alt="Miembro del equipo 2">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/f48c06/ffffff/?text=3" alt="Miembro del equipo 3">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/4a4e4d/ffffff/?text=4" alt="Miembro del equipo 4">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/f48c06/ffffff/?text=5" alt="Miembro del equipo 5">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/1281e6/ffffff/?text=6" alt="Miembro del equipo 6">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/4a4e4d/ffffff/?text=7" alt="Miembro del equipo 7">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/f48c06/ffffff/?text=8" alt="Miembro del equipo 8">
        </div>
        <div class="grid-item">
          <img src="https://via.placeholder.com/150x150/1281e6/ffffff/?text=9" alt="Miembro del equipo 9">
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.about-us {
  margin: 0 auto;
  max-width: 800px;
}

.section {
  margin-bottom: 50px;
}

h2 {
  color: #1c2b3a;
  font-size: 24px;
  font-weight: bold;
  margin-bottom: 20px;
}

p {
  color: #4a4e4d;
  font-size: 16px;
  line-height: 1.5;
}

.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 20px;
}

.grid-item img {
  width: 100%;
  height: auto;
}

.grid-item:nth-child(1) img {
  background-color: #4a4e4d;
}

.grid-item:nth-child(2) img {
  background-color: #1281e6;
}

.grid-item:nth-child(3) img {
  background-color: #f48c06;
}

.grid-item:nth-child(4) img {
  background-color: #4a4e4d;
}

.grid-item:nth-child(5) img {
  background-color: #f48c06;
}

.grid-item:nth-child(6) img {
  background-color: #1281e6;
}

.grid-item:nth-child(7) img {
  background-color: #4a4e4d;
}

.grid-item:nth-child(8) img {
  background-color: #f48c06;
}

.grid-item:nth-child(9) img {
  background-color: #1281e6;
}
</style>