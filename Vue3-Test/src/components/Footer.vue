<template>
  <footer>
    <div class="contenedor-footer">
      <div class="container d-flex justify-content-between align-items-center">
        <h3>Llamar a :<span id="numberHeader"></span></h3>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  // Your component's JavaScript logic goes here
};
</script>

<style lang="scss" scoped>
.contenedor-footer {
  display: flex;
  align-items: center;
  background-color: #414141;
  color: #fff;
  height: auto;
  /* position: absolute; */
  position: sticky;
  bottom: -40px;
  margin-bottom: 0;
  width: 100%;
  padding: 30px;
  h3, span {
    color: #fff;
  }
}
</style>