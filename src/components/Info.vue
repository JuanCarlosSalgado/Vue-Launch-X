<template>
  <div class="datos">
    <div class="card">
    <h1>Visitanos en:</h1>
    <p>Av.Paquita la del barrio #1234</p>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3747.0303068317126!2d-101.51873698520646!3d20.09101992450284!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x842c51d3b3e8a4d1%3A0xa5ca3821ffeebbb4!2sPasteler%C3%ADa%20la%20Estrella!5e0!3m2!1ses-419!2smx!4v1649002982967!5m2!1ses-419!2smx"
      width="400"
      height="300"
      style="border: 0"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe>      
    </div>
    <div class="horario">
      <h3>Horario de atencion</h3>
      <p>Lunes a domingo: 9am - 9pm</p>
      <h3>Telefono</h3>
      <p>4435892450</p>
    </div>

  </div>
</template>

<script>
export default {
  name: "Info",
};
</script>

<style scoped>
.datos {
  background-color: #e5e5f7;
  background-image: radial-gradient(
    rgba(172, 120, 119, .7) 1.35px,
    #ffebeb 1.35px
  );
  background-size: 27px 27px;
  padding-top: 3rem;
  padding-bottom: 3rem;
}
.horario h3 {
  margin: 10px;
}
</style>