<script setup lang="ts">
import MyEditor from "./components/MyEditor.vue";
</script>

<template>
  <div>
    <h2>Вы напечатали:</h2>
    [тут выводить значение напечатанное в DIV]
  </div>
  <div style="margin: 20px 0">
    <button>reset</button>
  </div>
  <MyEditor />
</template>
