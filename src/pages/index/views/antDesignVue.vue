<template>
  <a-space>
    <a-button @click="back">返回</a-button>
  </a-space>
</template>

<script setup lang="ts">
import { useRouter } from "vue-router"

const router = useRouter()
const back = () => {
  router.back()
}
</script>

<style>
</style>
