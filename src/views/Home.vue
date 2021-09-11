<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from '../components/HelloWorld.vue'
</script>

<template>
<img alt="Vue logo" src="../assets/logo.png" class="inline" ><HelloWorld msg="Hello Vue 3 + TypeScript + Vite + WindiCSS"></HelloWorld>
</template>

<script lang="ts">
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    HelloWorld
  },
};
</script>
