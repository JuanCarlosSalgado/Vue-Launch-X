<template>
    <div class="flex">
        <div class="Pasteles">
            <img width="200" src="@/assets/Boda.png"  alt="Imagen 1">
            <h1>Adornos de Boda</h1>
            <p>150 Pesos</p>
        </div>
        <div class="Pasteles">
            <img width="200" src="@/assets/Cumple.png"  alt="Imagen 1">
            <h1>Adornos de Cumpleaños</h1>
            <p>130 Pesos</p>
        </div>
        <div class="Pasteles">
            <img width="200" src="@/assets/15.png"  alt="Imagen 1">
            <h1>Adornos de XV</h1>
            <p>100 Pesos</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "Adornos",
}
</script>

<style scoped>
.flex {
    display: flex;
    justify-content: space-between;
    margin-left: 150px;
    margin-right: 150px;
    padding-top: 50px;
    padding-bottom: 50px;
    
}
.Pasteles {
    align-content: center;
    position: relative;
    padding-left: 3rem;
    padding-right: 3rem;
}
</style>