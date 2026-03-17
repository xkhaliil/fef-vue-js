<script setup lang="ts">
import { ref } from 'vue'
const count = ref(0)
function increment() {
  count.value++
}
</script>

<template>
  <main>
    <div class="flex flex-col items-center justify-center h-screen space-y-10">
      <div class="mb-24">Counter</div>
      <button
        v-on:click="increment"
        class="border border-green-700 p-9 rounded-2xl shadow-2xl hover:bg-green-700 hover:text-white transition duration-300"
      >
        Increment
      </button>
      <div>
        <span class="text-2xl">{{ count }}</span>
      </div>
    </div>
  </main>
</template>
