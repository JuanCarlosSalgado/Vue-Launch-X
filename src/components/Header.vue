<template>
  <header class="site-header inicio">
    <div class="contenedor contenido-header">
      <div class="barra">
        <h1>Pasteleria SIUU</h1>

        <nav class="navegacion">
          
          <router-link to="/">Comprar</router-link> |
          <router-link to="/about">Pagina del pastelero</router-link>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.site-header.inicio {
  text-decoration: none;
  background-position: center center;
  background-size: cover;
  min-height: 12vh;
}

.barra {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-left: 3rem;
  margin-right: 3rem;
}

.barra h1 {
  color: rgb(172, 120, 119);
  margin-left: 12rem;
  font-weight: 700;
}
</style>