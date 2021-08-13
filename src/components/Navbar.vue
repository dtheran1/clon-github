<template>
  <div id="nav">
    <ul>
      <img src="../assets/logogit.png" alt="logo" width="100%" ref="#"/>
      <input type="search" placeholder="   Search by user... " />
      <li><router-link to="/">Home</router-link></li>
      <li>
        <router-link to="/repositorios">Repositorios</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>
<style scoped>
#nav {
  display: block;
  width: 100%;
  height: 60px;
  position: fixed;
  text-align: center;
  color: white;
  background: rgb(56, 55, 55);
  border-radius: 5px;
  font-size: 15px;
  box-shadow: 0 0 10px 1px rgb(19, 19, 19);
  
}

#nav ul {
  display: block;
  padding: 14px;
  list-style-type: none;
  
}
#nav li {
  display: inline-block;
  margin-left: 30px;
  line-height: 30px;
  vertical-align: top;
}
#nav input {
  margin-right: 30px;
  color: rgb(158, 158, 158);
  font-size: 15px;
  font-weight: bold;
  border-radius: 5px;
  padding-top: 10px;
  width: 40%;
  background-color: #ccc;
  
}
#nav img {
  width: 28px;
  height: 28px;
  margin-left: -13%;
  margin-right: 20px;
  cursor:pointer;
}
#nav a.router-link-exact-active {
  color: #ffffff;
}

#nav a:hover {
  color: #5f5f5f;
}

#nav a {
  display: block;
  font-weight: bold;
  color: #000000;
  padding-left: 18px;
  padding-right: 10px;
  text-decoration: none;
  transition: all 300ms;
}
</style>