<script setup lang="ts">
import MyEditor from "./components/MyEditor.vue";
import { ref } from "vue";

const text = ref("Init text");
</script>

<template>
  <div>
    <h2>Вы напечатали:</h2>
    {{ text }}
  </div>
  <div style="margin: 20px 0">
    <button @click="text = ''">reset</button>
  </div>
  <MyEditor v-model="text" />
</template>
