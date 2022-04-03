<template>
<div class="Centrar">
<table class="centro">
        <tr>
            <th>Sabores</th>
            <th>Cantidad Restante</th>
        </tr>
        <tr>
            <td>Chocolate</td>
            <td>{{$store.state.Chocolate}}</td>
        </tr>
        <tr>
            <td>Vainilla</td>
            <td>{{$store.state.Vainilla}}</td>
        </tr>
        <tr>
            <td>Fresa</td>
            <td>{{$store.state.Fresa}}</td>
        </tr>
    </table><br>

    <table class="centro">
        <tr>
            <th>Adornos</th>
            <th>Cantidad Restante</th>
        </tr>
        <tr>
            <td>XV Años</td>
            <td>{{$store.state.XV}}</td>
        </tr>
        <tr>
            <td>Cumpleaños</td>
            <td>{{$store.state.Cumple}}</td>
        </tr>
        <tr>
            <td>Boda</td>
            <td>{{$store.state.Boda}}</td>
        </tr>
    </table><br>
    
    <table class="centro">
        <tr>
            <th>No.Pedido</th>
            <th>Nombre</th>
            <th>Telefono</th>
            <th>Correo Electronico</th>
            <th>Descripcion</th>
            <th>Sabores</th>
            <th>Adornos</th>
        </tr>
        <tr>
            <td>{{$store.state.No}}</td>
            <td>{{$store.state.Nombre}}</td>
            <td>{{$store.state.Tel}}</td>
            <td>{{$store.state.Correo}}</td>
            <td>{{$store.state.Des}}</td>
            <td>{{$store.state.Sabor}}</td>
            <td>{{$store.state.Adorno}}</td>
        </tr>
    </table>
</div>
    
</template>

<script>
export default {
    name: "Table",
}
</script>

<style scoped>
.Centrar {
    background-color: #fafafa;
  margin: 1rem;
  padding: 1rem;
  border: 2px solid #ccc;
}
.centro {
    display: inline;
    justify-content: center;
}
</style>