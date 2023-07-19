<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <img
      src="https://github.com/Jimmyluluu/image/blob/master/Standingsign.png?raw=true"
    />
    <img
      src="https://github.com/Jimmyluluu/image/blob/master/Card.png?raw=true"
    />
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
