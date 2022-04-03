<template>
    <div class="cont gris">
        <div class="">
          <h3>@2021 Pasteleria SIUU. All rights reserved</h3>
        </div>
        <div class="item">
          <div>
            <h3>Terms & Agrements</h3>
          </div>
          <div>
            <h3>Privacy Policy</h3>
          </div>
          
        </div>
    </div>
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style scoped>

.cont {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  flex-direction: row;
  padding-left: 8rem;
  padding-right: 8rem;
  padding-bottom: 3rem;
  padding-top: 3rem;
  background-color: #ac7877;
}

.gris {
  color: white;
}

.item {
  display: flex;
}

</style>