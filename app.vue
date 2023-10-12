<script setup lang="ts">
const route = useRoute()
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
import "./assets/css/input.css"

onMounted(() => {
  initFlowbite();
})

</script>

<template>
  <div>
    <NuxtPage></NuxtPage>
  </div>
</template>
