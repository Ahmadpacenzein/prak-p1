<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      AHMAD ZAINI GANTENG
    </p>
  </div>

  <p>
    Ini adalah tampilan dari web saya seorang mahasiswa yang sedang belajar PBK
  </p>

  <h5>Silahkan Ikuti Perkembangan saya</h5>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
