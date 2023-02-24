<template>
    
    <div class="login-container">
      <form>
        <h2>Iniciar sesión</h2>
        <div class="form-group">
          <label for="email">Correo electrónico:</label>
          <input type="email" id="email" v-model="email" required>
        </div>
        <div class="form-group">
          <label for="password">Contraseña:</label>
          <input type="password" id="password" v-model="password" required>
        </div>
        <button type="submit">Iniciar sesión</button>
      </form>
    </div>
  </template>
  <script>
  export default {
    data() {
      return {
        email: '',
        password: ''
      }
    }
  }
  </script>
  
  <style>
  .login-container {
    display: flex;
    justify-content: center;
    align-items: top;
    height: 50vh;
  }
  
  form {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 300px;
    padding: 20px;
    background-color: #F98836;
    border-radius: 10px;
    margin-bottom: 20px;
  }
  
  h2 {
    margin-top: 0;
    color: white;
  }
  
  .form-group {
    display: flex;
    flex-direction: column;
  margin-bottom: 10px;
}

    label {
  margin-bottom: 5px;
  color: white;
}

input {
  padding: 5px;
  border-radius: 5px;
  border: none;
  outline: none;
}

button {
  padding: 10px;
  border-radius: 5px;
  border: none;
  outline: none;
  background-color: #003049;
  color: #ffff;
  cursor: pointer;
}
</style>