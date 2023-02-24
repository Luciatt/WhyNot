<template>
    <header>
      <img src="../assets/whynot3.png" alt="logo">
      <h1>Let your project take off</h1>
    </header>
    
<NavBar/>
    
  </template>
  <script>
import NavBar from './NavBar.vue';
</script>
  
  <style scoped>
  header {
    background:#f98836;
    position: relative;
    width: 100%;
    height: 10vw;
    background-color: #F98836;
  }


  
  h1 {
  
    font-size: 5vw;
    color: white;
;
    font-weight: normal;
    position: absolute;
    top: 0vw;
    left: 15vw;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
  }
  
  header img {
    width: 13%;
    margin: 10px 10px 0 20px;
    border-radius: 200px;
  }
  
  @media (max-width:500px) {
    header img {
      width: 28%;
      margin: 8px 0 0 5.9%;
    }
  }
  </style>