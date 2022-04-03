<template>
<div class="all">
    <h2>Nuestros Pasteles</h2>
<div class="flex">

        <div class="Pasteles">
            <img width="200" src="@/assets/Chocolate.png"  alt="Imagen 1">
            <h1>Chocolate</h1>
            <p>150 Pesos</p>
        </div>
        <div class="Pasteles">
            <img width="200" src="@/assets/Vainilla.png"  alt="Imagen 1">
            <h1>Vainilla</h1>
            <p>130 Pesos</p>
        </div>
        <div class="Pasteles">
            <img width="200" src="@/assets/Fresa.jpg"  alt="Imagen 1">
            <h1>Fresa</h1>
            <p>100 Pesos</p>
        </div>
    </div>
</div>
    
</template>

<script>
export default {
    name: "Pasteles",
}
</script>

<style scoped>
.all {
    background-color: #ac7877;
    padding: 3rem;
}
.all h2 {
    font-size: 3rem;
    color: white;
}
.flex {
    display: flex;
    justify-content: space-between;
    margin-left: 150px;
    margin-right: 150px;
}
.Pasteles {
    align-content: center;
    color: black;
    background-color: white;
    border-radius: 10%;
    padding: 3rem;
}
</style>