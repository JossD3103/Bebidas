<script setup>

</script>

<template>
  <header>
    <div class="mx-auto container px-5 py-16">
      <div>

      </div>
      <form action=""
        class="md:w-1/2 2xl:w-1/3 bg-orange-400 my-32 p-10 rounded-lg shadow space-y-6">
        
        <div class="space-y-4">
          <label 
            class="block text-white uppercase font-extrabold text-lg"
            for="ingredient">Nombre o Ingredientes</label>
            <input 
              id="ingredient"
              type="text"
              class="p-3 w-full rounded-lg focus:outline-none"
              placeholder="Nombre o INgrediente: ej. Vodka, Tequila"
            >
        </div>
        <div class="space-y-4">
          <label 
            class="block text-white uppercase font-extrabold text-lg"
            for="category">Categoria</label>

            <select 
              id="category"
              class="p-3 w-full rounded-lg focus:outline-none"
            >
            <option value="">-- Seleccione --</option>
            </select>
        </div>
        <input 
          type="submit"
          value="Search Recipes"
          class=""
        >
      </form>
    </div>
  </header>
</template>

