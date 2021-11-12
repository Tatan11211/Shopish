<template>
  <div id="nav">
    <router-link to="/" class="link">Inicio</router-link>
    <router-link to="/camping" class="link">Camping</router-link>
    <router-link to="/contactus"  class="link">Contactenos</router-link>
  </div>
</template>

<style scoped>
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.link {
    margin: 5px;
}
</style>