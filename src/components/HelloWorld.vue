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
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    <a href="" target="_blank"
      >BIENVENIDOS</a
    >, 
  </p>
  <p>
     Más Información
    <a
      href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support"
      target="_blank"
      ></a
    >
  </p>
  <p class="read-the-docs">Sigueme</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
