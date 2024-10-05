<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
  <!-- <div
    class="flex h-screen items-center justify-center bg-white dark:bg-gray-800"
  >
    <button
      class="py-4 px-6 w-96 font-bold font-mono rounded-md transition-all text-white bg-blue-700 hover:bg-blue-800 active:bg-blue-900 dark:text-black dark:bg-blue-400 dark:hover:bg-blue-500 dark:active:bg-blue-600"
    >
      Hello Tailwind
    </button>
  </div> -->
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
