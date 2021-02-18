<template>
  <div class="fondo">
    <NavBar />
    <Tarea />
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import Tarea from "./components/Tarea";

export default {
  name: "App",
  components: {
    NavBar,
    Tarea,
  },
};
</script>

<style>
.fondo {
  background-image: url("./assets/fondo.jpg");
  height: 100vh;
}
</style>
