
<template>
  <h1 class="text-3xl font-bold underline">
    Hola Mundo!!
    <!--mis componentes-->
    <div id="boton">
      <Boton/>

    </div>
  </h1>

</template>
  <script setup>
  import Boton from "@/components/Boton.vue";
  export default {
    name: "Boton",
    components: {
      Boton
    }
  };
  
  </script>

<style scoped>

</style>
