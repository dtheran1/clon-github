<template>
  <div class="form">
      <form action="" @submit.prevent="formData"  >
        <h1>Inicia Sesión</h1>
        <div class="columns">
          <div class="field-container">
            <p>Nombre:</p>
            <i class="fas fa-user-circle"></i>
            <input
              required
              type="text"
              class="field"
              placeholder="Nombres"
              v-model="nombre"
            />
          </div>

          <div class="field-container">
            <p>Apellidos:</p>
            <i class="fas fa-user-circle"></i>
            <input
              required
              type="text"
              class="field"
              placeholder="Apellidos"
              v-model="apellido"
            />
          </div>
        </div>

        <p>Número de CC:</p>
        <div class="field-container">
          <i class="fas fa-id-card"></i>
          <input
            required
            type="number"
            class="field"
            placeholder="Cedula"
            v-model="cc"
          />
        </div>

        <p>Fecha de nacimiento:</p>
        <div class="field-container">
          <i class="fas fa-calendar-day"></i>
          <input
            required
            type="date"
            class="field"
            placeholder="Nombres"
            v-model="date"
          />
        </div>

        <p>Email:</p>
        <div class="field-container">
          <i class="fas fa-at"></i>
          <input
            required
            type="email"
            class="field"
            placeholder="Email"
            v-model="email"
          />
        </div>

        <p>UserName:</p>
        <div class="field-container">
          <i class="fas fa-user-check"></i>
          <input
            required
            type="text"
            class="field"
            placeholder="Usuario"
            v-model="username"
          />
        </div>
        <p>
          <button type="submit" >Iniciar Sesión</button>
        </p>
      </form>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>