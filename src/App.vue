<script setup>
import {ref} from "vue";

const count = ref(0);
</script>

<template>
  <main>
    <div>
      <h4>The current count is..</h4>
      <h1>{{ count }}</h1>
      <button @click="count--">-</button>
      <button @click="count++">+</button>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: skyblue;
  height: 100vh;
  width: 100vw;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 20px;
}

div{
  text-align: center;
}

button {
  height: 30px;
  width: 40px;
  margin: 10px;
}
</style>
