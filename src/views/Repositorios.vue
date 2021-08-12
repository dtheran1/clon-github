<template>
  <div class="container">
    <div class="user">
      <h1>Titulo del repositorio</h1>
      
      <hr>
    </div>
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
      <hr>
      
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
.container {
  min-height: 600px;
  width: 90%;
  padding-left: 10px;
  padding-bottom: 10px;
  margin: 0px auto;
  box-shadow: 0px 0px 40px black;
  padding-top: 70px;
}
.user {
  width: 60%;
  padding: 10px;
  text-align: justify;
  background-color: rgb(68, 66, 66);
  border-radius: 20px;
  box-shadow: 0 0 10px 1px rgb(19, 19, 19);
  height: 250px;
  margin-bottom: 20px;
}
</style>