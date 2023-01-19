<script setup lang="ts">
import { ref } from 'vue'
defineProps<{
  msg: string
}>()
let count = ref(0)
</script>

<template>
  <div class="">
    <h1 class="">{{ msg }}</h1>
    <h3>I’ve successfully created a project with VUE!</h3>
    <br />
    <div>
      <button class="bg-gray-700 p-2 rounded-lg text-white" @click="count++">
        Click me
      </button>
      <div>{{ count }}</div>
    </div>

    <img class="w-96" src="@/assets/realpic.jpg" alt="Picture of Westyn and Kiley" />
    <!-- <a href="https://vitejs.dev/" target="_blank" rel="noopener">Vite</a> +
      <a href="https://vuejs.org/" target="_blank" rel="noopener">Vue 3</a>. What's next? -->
  </div>
</template>

<style scoped>
/* h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
} */
</style>
