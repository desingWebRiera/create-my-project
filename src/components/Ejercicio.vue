<template>
    <div class="container mx-auto flex flex-col items-center justify-center bg-[#f6c3f6] text-[#bd808b] ">
    <h1 class="text-3xl font-bold ">
    Hello world!
  </h1>
     

        {{ title }}
    </div>
    <div class="broma">
        <vue-form-input placeholder="Nombre"></vue-form-input>
        <vue-form-input placeholder="Apellido"></vue-form-input>

    </div>
</template>
<script>
export default {
    name: "Ejercicio",
    data() {
        return{ 
            title: "Bienvenidos a mi proyecto"
        }
    },
    
    
};
</script>
<style>





</style>