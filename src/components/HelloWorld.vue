<template>
  <div class="app-container">
    <header class="header">
      <h1>{{ msg }}</h1>
      <p>
        Plataforma desarrollada en Vue.js para gestionar las <strong>importaciones de productos tecnológicos</strong> 
        hacia Tingo María, optimizando el proceso logístico y de seguimiento.
      </p>
    </header>

    <!-- Ventajas -->
    <section class="advantages">
      <h2>¿Por qué usar esta plataforma?</h2>
      <div class="advantage-cards">
        <div class="card">
          <h3>Gestión Eficiente</h3>
          <p>Organiza y gestiona importaciones de manera centralizada.</p>
        </div>
        <div class="card">
          <h3>Monitoreo en Tiempo Real</h3>
          <p>Controla cada etapa del proceso de importación de productos.</p>
        </div>
        <div class="card">
          <h3>Optimización Logística</h3>
          <p>Asegura entregas más rápidas y eficientes a Tingo María.</p>
        </div>
      </div>
    </section>

    <!-- Recursos Esenciales -->
    <section class="resources">
      <h2>Recursos Esenciales</h2>
      <ul>
        <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
        <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
        <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
        <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
        <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
      </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: {
      type: String,
      default: "Importaciones de Productos Tecnológicos - Tingo María"
    }
  }
};
</script>

<!-- Estilos del Componente -->
<style scoped>
.app-container {
  padding: 20px;
  max-width: 960px;
  margin: auto;
  font-family: Arial, sans-serif;
}

.header {
  text-align: center;
  margin-bottom: 40px;
}

.advantages {
  margin-top: 40px;
}

.advantage-cards {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  background-color: #f5f5f5;
  padding: 20px;
  border-radius: 10px;
  width: 300px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}

.card:hover {
  transform: scale(1.05);
}

.resources ul {
  list-style-type: none;
  padding: 0;
  text-align: center;
}

.resources li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
