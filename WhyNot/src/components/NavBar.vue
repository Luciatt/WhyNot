<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/"> Home </RouterLink>
    <RouterLink to="/aboutUs"> About </RouterLink>
    <RouterLink to="/login"> Login </RouterLink>
    <RouterLink to="/register"> Register </RouterLink>


  </nav>
</template>

<style scoped>

nav {
  font-family: "Kreon", sans-serif;
  display: flex;
  justify-content: end;
  position: sticky;
  bottom:10vw;
  z-index: 10000;
  margin-bottom: 50px;
  border-color:#73CDD2
}

a {
  text-decoration: none;
  color: #F98836;
  font-weight: bold;
  display: inline-block;
  height: 47px;
  padding: 0 20px;
  line-height: 47px;
}

nav a:hover,
nav a.router-link-exact-active:hover {
  color: #73CDD2;
  background-color: #fff;
}

nav a.router-link-exact-active {
  color: #73CDD2;
  background-color: #fff;
}

@media (max-width:500px) {
  nav {
    display: flex;
    flex-direction: column;
    position: sticky;
    top: 0;
    z-index: 10000;
    margin-bottom: 50px;
    text-align: center;
  }
}
</style>
