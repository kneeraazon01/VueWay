<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});
const count = ref(5);
</script>

<!--  -->
<template>
  <h1>{{ msg }}</h1>
  <button type="button" @click="count += 5">
    Ouchh!! You biatch clicked me {{ count }} times already
  </button>
</template>

<!--  -->
<style scoped>
a {
  color: #42b983;
}
button {
  background-color: #115c3a;
  color: #fff;
  font-size: 24px;
  padding: 6px 16px;
  border-radius: 15px;
  border: 2px solid;
}
</style>
