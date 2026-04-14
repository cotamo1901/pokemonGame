<template>
  <section class="mt-5">
    <ul>
      <li>Pokemon 1</li>
      <li>Pokemon 2</li>
      <li>Pokemon 3</li>
      <li>Pokemon 4</li>
    </ul>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
@reference "@/assets/styles.css";
li {
  @apply m-2 w-40 cursor-pointer rounded-md bg-white text-center shadow-md transition-all hover:bg-gray-100;
}
</style>
