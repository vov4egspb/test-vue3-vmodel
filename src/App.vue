<template>
  <div>
    <h2>Вы напечатали:</h2>
    {{ text }}
  </div>
  <div style="margin: 20px 0">
    <button>reset</button>
  </div>
  <MyEditor v-model="text" />
</template>

<script setup lang="ts">
import { ref } from 'vue';
import MyEditor from "./components/MyEditor.vue";

const text = ref('');
</script>
