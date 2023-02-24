<script>

</script>

<template>
  <form>
    <div>
      <label for="fullname">Nombre completo</label>
      <input type="text" id="fullname" name="fullname" required>
    </div>
    <div>
      <label for="email">Correo electrónico</label>
      <input type="email" id="email" name="email" required>
    </div>
    <div>
      <label for="password">Contraseña</label>
      <input type="password" id="password" name="password" required>
    </div>
    <div>
      <label for="confirm-password">Confirmar contraseña</label>
    <input type="password" id="confirm-password" name="confirm-password" required>
    </div>
    <div>
      <label for="birthdate">Fecha de nacimiento</label>
      <input type="date" id="birthdate" name="birthdate" required>
    </div>
    <div>
      <label for="gender">Género</label>
      <select id="gender" name="gender" required>
        <option value="">Seleccione una opción</option>
        <option value="masculino">Masculino</option>
        <option value="femenino">Femenino</option>
        <option value="otro">Otro</option>
      </select>
    </div>
    <div>
      <label for="country">País/Región</label>
      <input type="text" id="country" name="country" required>
    </div>
    <div>
      <label for="interests">Intereses/Preferencias</label>
      <textarea id="interests" name="interests"></textarea>
    </div>
    <div>
      <label>
        <input type="checkbox" name="newsletter"> Recibir boletines o notificaciones
      </label>
    </div>
    <div>
      <label>
        <input type="checkbox" name="accept-terms" required> Acepto la política de privacidad y términos y condiciones
      </label>
    </div>
    <button type="submit">Registrarse</button>
  </form>

  </template>


<style scoped>

form {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  margin: 0 auto;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
  background-color: #fff;
}

form label {
  display: block;
  font-size: 14px;
  font-weight: bold;
  margin-bottom: 5px;
}
form input[type="text"],
form input[type="email"],
form input[type="password"],
form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: none;
  border-radius: 5px;
  background-color: #f9f9f9;
  color: #333;
}

form input[type="checkbox"] {
  margin-right: 10px;
}
form button[type="submit"] {
  width: 100%;
  padding: 10px;
  border: none;
  border-radius: 5px;
  background-color: #003049;
  color: #fff;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
}

/* Estilos para los campos requeridos */
form [required] {
  border: 2px solid #fcb800;
  box-shadow: none;
}
/* Estilos para el campo de género */
form select {
  appearance: none;
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: none;
  border-radius: 5px;
  background-color: #f9f9f9;
  color: #333;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'%3E%3Cpath fill='%23ccc' d='M12 14.83l4.55 3.4-1.64-5.54L19 8.9l-5.74-.48L12 3.5 9.74 8.42 4 8.9l4.09 3.79-1.64 5.54L12 14.83z'/%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: right 10px center
}

/* Estilos para los campos de la política de privacidad y términos y condiciones */
form [required]:valid + label::after {
  content: " ✓";
  color: green;
}




body {
  background-color: #f5f5f5;
}

h1 {
  text-align: center;
  font-size: 24px;
  font-weight: bold;
  color: #333;
  margin-top: 50px;
  margin-bottom: 20px;
}
.error {
  color: red;
  margin-top: 5px;
  margin-bottom: 20px;
  font-size: 14px;
}

.success {
  color: green;
  margin-top: 5px;
  margin-bottom: 20px;
  font-size: 14px;
}

</style>