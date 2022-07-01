<template>
  <div class="hello">Hello Nuxt {{ version }}!</div>
</template>
<script lang="ts" setup>
import { useError } from "#app";
const error = useError();
console.log(error);
console.log(12);
</script>
<style scoped>
.hello {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 3rem;
  padding: 10rem;
}
</style>


