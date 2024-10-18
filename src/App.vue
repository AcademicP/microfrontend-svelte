<template>
  <div id="app">
    <header class="app-header">
      <img alt="Vue logo" src="./assets/logo.png" class="logo" />
      <h1>Importaciones de Productos Tecnológicos</h1>
      <p>Tingo María - Desarrollado en Vue.js</p>
    </header>
    <HelloWorld msg="Bienvenido a la Plataforma de Importaciones Tecnológicas" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld
  }
};
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #f5f5f5;
  color: #2c3e50;
  margin-top: 20px;
  padding: 40px;
}

.app-header {
  margin-bottom: 40px;
}

.logo {
  height: 100px;
  margin-bottom: 20px;
}

h1 {
  color: #42b983;
  margin-bottom: 10px;
}

p {
  font-size: 18px;
  color: #2c3e50;
}
</style>
