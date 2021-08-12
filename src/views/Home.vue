<template>
  <div class="container">
    <div class="user">
      <h1>Titulo del repositorio</h1>
      <h2>Nombre de usuario</h2>
      <br />
      <p>
        <span>UserName</span><br />
        <span>Email</span><br />
        <span>Fecha de nacimiento</span><br />
        <span>Documentos</span>
      </p>
    </div>
    <div class="form">
      <form action="">
        <h1>Inicia Sesión</h1>
        <div class="columns">
          <div class="field-container">
            <p>Nombre:</p>
            <i class="fas fa-user-circle"></i>
            <input type="text" class="field" placeholder="Nombres" />
          </div>

          <div class="field-container">
            <p>Apellidos:</p>
            <i class="fas fa-user-circle"></i>
            <input type="text" class="field" placeholder="Apellidos" />
          </div>
        </div>

        <p>Número de CC:</p>
        <div class="field-container">
          <i class="fas fa-id-card"></i>
          <input type="number" class="field" placeholder="Cedula" />
        </div>

        <p>Fecha de nacimiento:</p>
        <div class="field-container">
          <i class="fas fa-calendar-day"></i>
          <input type="date" class="field" placeholder="Nombres" />
        </div>

        <p>Email:</p>
        <div class="field-container">
          <i class="fas fa-at"></i>
          <input type="email" class="field" placeholder="Email" />
        </div>

        <p>UserName:</p>
        <div class="field-container">
          <i class="fas fa-user-check"></i>
          <input type="text" class="field" placeholder="Usuario" />
        </div>
        <p>
          <button type="submit">Iniciar Sesión</button>
        </p>
      </form>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
.container {
  display: flex;

  /* flex-direction: column; */

  min-height: 600px;
  width: 90%;
  padding-left: 10px;
  padding-bottom: 10px;
  margin: 0px auto;
  box-shadow: 0px 0px 40px black;
  padding-top: 70px;
  color: white;
}
.user {
  width: 50%;
  padding: 10px;
  margin-left: 40px;
  margin-top: 20px;
  text-align: justify;
  background-color: rgb(44, 43, 43);
  border-radius: 20px;
  box-shadow: 0 0 10px 1px rgb(19, 19, 19);
  height: 300px;
  margin-bottom: 20px;
  border-bottom: 1px solid rgb(243, 243, 243);
}

.form {
  float: right;
  width: 30%;
  height: 450px;
  padding: 20px;
  margin-top: 20px;
  margin-left: 30px;
  text-align: center;
  background-color: rgb(44, 43, 43);
  box-shadow: 0 0 10px 1px rgb(19, 19, 19);
  border-radius: 20px;
  border-bottom: 1px solid rgb(243, 243, 243);
  color: #999;
}
.form h1 {
  color: white;
  border-bottom: 1px solid gray;
  margin-bottom: 10px;
}

.form input {
  outline: none;
}

.field {
  border: 1px solid rgb(250, 250, 249);
  padding: 6px;
  margin-top: 3px;
  width: 80%;
  margin-bottom: 6px;
  border-radius: 0px 4px 4px 0;
}

.field:focus {
  border-color: rgb(55, 247, 208);
}

.field-container div {
  display: inline-block;
  vertical-align: top;
}

.field-container i {
  border: 1px solid #ccc;
  padding: 6px 6px 7px 6px;
  background-color: #ddd;
  color: #888;
  border-radius: 4px 0 0 4px;
}

.columns div {
  display: inline-block;
  vertical-align: top;
  width: 50%;
}

.columns .field{
  width: 60%;
}

.form button {
  margin-top: 20px;
  line-height: 13px;
  padding: 5px;
  border: none;
  cursor: pointer;
  background-color: transparent;
  transition: all 300ms;
  border-radius: 20px;
  color: white;
  font-weight: bold;
  width: 75%;
}

.form button:hover {
  background: #ccc;
  color: black;
}
</style>