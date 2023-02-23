<template>
    <header>
      <img src="../assets/whynot3.png" alt="logo">
      <h1>Let your project take off</h1>
    </header>
  </template>
  
  <style scoped>
  header {
    background: linear-gradient(90deg, #000986 10%, #F98836 90%);
    position: relative;
    width: 100%;
    height: 20vw;
  }

  img{
    border-radius: 15;
  }
  
  h1 {
  
    font-size: 5vw;
    color: #fff;
    font-weight: normal;
    position: absolute;
    top: 10vw;
    left: 33vw;
  }
  
  header img {
    width: 28%;
    margin: 8px 0 0 5.9%;
  }
  
  @media (max-width:500px) {
    header img {
      width: 28%;
      margin: 8px 0 0 5.9%;
    }
  }
  </style>