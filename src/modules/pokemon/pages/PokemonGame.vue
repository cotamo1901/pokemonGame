<template>
  <section v-if="false" class="flex h-screen w-screen flex-col items-center justify-center">
    <h1 class="text-3xl">Espere por favor</h1>
    <h3 class="animate-pulse">Cargando Pokemon</h3>
  </section>

  <section class="flex h-screen w-screen flex-col items-center justify-center">
    <h1 class="m-5">¿ Quien es este Pokemon?</h1>

    <PokemonPicture/>
    <PokemonOptions/>
  </section>
</template>

<script setup lang="ts">
import PokemonOptions from '../components/PokemonOptions.vue';
import PokemonPicture from '../components/PokemonPicture.vue';
import { usePokemon } from '../composables/usePokemonGame';

const {gameStatus} =usePokemonGame();

</script>

<style scoped></style>
