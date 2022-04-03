<template>
  <div class="all">
    <div></div>
    <div class="card">
      <h1>Haz tu pedido!</h1>
      <div class="flex-text">
        <label for="Nombre">Introduzca su nombre</label>
        <div class="end">
          <input
            type="text"
            id="Nombre"
            name="Nombre"
            value="Nombre"
          /><br /><br />
        </div>
      </div>
      <div class="flex-text">
        <label for="Nombre">Introduzca su Telefono</label>
        <div class="end">
          <input
            type="number"
            id="Telefono"
            name="Telefono"
            value="Telefono"
          /><br /><br />
        </div>
      </div>
      <div class="flex-text">
        <label for="Correo">Introduzca su Correo</label>
        <div class="end">
          <input
            type="email"
            id="Correo"
            name="Correo"
            value="Correo"
          /><br /><br />
        </div>
      </div>
      <div class="flex-text">
        <label for="Des">Observaciones</label>
        <div class="end">
          <input
            type="text"
            id="Des"
            name="Des"
            value="Descripcion"
          /><br /><br />
        </div>
      </div>

      <div class="flex">
        <label for="">Sabor Principal: </label><br /><br />
        <div class="end-tl">
          <div class="1">
            <input type="radio" id="Sabor1" name="Sabor" value="Chocolate" />
            <label for="Sabor1">Chocolate</label><br /><br />
          </div>
          <div class="2">
            <input type="radio" id="Sabor2" name="Sabor" value="Vainilla" />
            <label for="Sabor2">Vainilla</label><br /><br />
          </div>
          <div class="3">
            <input type="radio" id="Sabor3" name="Sabor" value="Fresa" />
            <label for="Sabor3">Fresa</label><br /><br />
          </div>
        </div>
      </div>

      <div class="flex">
        <label for="">Sabor Secundario:</label><br /><br />
        <div class="end-tl">
          <div class="1">
            <input type="radio" id="Sabor1" name="Sabor2" value="Chocolate" />
            <label for="Sabor1">Chocolate</label><br /><br />
          </div>
          <div class="2">
            <input type="radio" id="Sabor2" name="Sabor2" value="Vainilla" />
            <label for="Sabor2">Vainilla</label><br /><br />
          </div>
          <div class="3">
            <input type="radio" id="Sabor3" name="Sabor2" value="Fresa" />
            <label for="Sabor3">Fresa</label><br /><br />
          </div>
          <div class="4">
            <input type="radio" id="Sabor4" name="Sabor2" value="Ninguno" />
            <label for="Sabor4">Ninguno</label><br /><br />
          </div>
        </div>
      </div>

      <div class="flex">
        <label for="">Adornos:</label><br /><br />
        <div class="end-tl">
          <div class="1">
            <input type="checkbox" id="XV Años" name="XV" value="tipo1" />
            <label for="XV Años">XV Años</label><br /><br />
          </div>
          <div class="2">
            <input
              type="checkbox"
              id="Cumpleaños"
              name="Cumpleaños"
              value="tipo2"
            />
            <label for="Cumpleaños">Cumpleaños</label><br /><br />
          </div>
          <div class="3">
            <input type="checkbox" id="Boda" name="Boda" value="tipo3" />
            <label for="Boda">Boda</label><br /><br />
          </div>
        </div>
      </div>

      <div class="flexbtn">
        <div class="btn">
          <input type="reset" />
        </div>
        <div class="btn">
          <input type="submit" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Forms",
};
</script>

<style scoped>
.all {
  background-color: #e5e5f7;
  background-image: radial-gradient(
    rgba(172, 120, 119, 0.7) 1.35px,
    #ffebeb 1.35px
  );
  background-size: 27px 27px;
  padding-top: 3rem;
}
.card {
  margin-left: 30%;
  margin-right: 30%;
  padding: 3rem;
  text-align: center;
  background-color: #ac7877;
  border-radius: 10%;
}
.flex {
  display: flex;
  justify-content: space-between;
}
.flexbtn {
  display: flex;
  justify-content: space-evenly;
}
.flexbtn input {
  width: 7rem;
  color: white;
  background-color: #ac7877;
}
.flex-text {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 3px;
}
.end-tl {
  display: flex;
}
</style>
