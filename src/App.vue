<script setup>
import {ref} from "vue";

const count = ref(0);
</script>

<!-- the template: IT's needed to run properly -->
<template>
  <main>
    <div>
      <h4>The Current count is ...</h4>
      <h1>{{ count }}</h1>
      <button @click="count--">-</button>
      <button @click="count++">+</button>
    </div>
  </main>
</template>

<style scoped>
main {
  /* background-color: aliceblue; */
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
}

div {
  text-align: center;
}
</style>
