<script setup lang="ts">
import { greet, l } from "picky";

const cl = () => {
  l("Hellooolll!");
};
</script>

<template>
  <div>
    <button @click="cl">Interoperate</button>
  </div>
</template>
