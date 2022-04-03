<template>
    <section>
      <div class="curve"></div>
    </section>
</template>

<script>
export default {
    name: "Wavedown",
}
</script>

<style scoped>
section {
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100px;
    background: #ac7877;
}

.curve {
    position: absolute;
    height: 250px;
    width: 100%;
    bottom: 0;
    text-align: center;
}

.curve::before {
    content: '';
    display: block;
    position: absolute;
    border-radius: 100% 50%;
    width: 55%;
    height: 100%;
    transform: translate(85%, 60%);
    background-color: hsl(0, 0%, 100%);
}

.curve::after {
    content: '';
    display: block;
    position: absolute;
    border-radius: 100% 50%;
    width: 55%;
    height: 100%;
    background-color: #ac7877;
    transform: translate(-4%, 40%);
    z-index: -1;
}
</style>