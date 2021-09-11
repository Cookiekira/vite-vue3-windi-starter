<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from "../components/HelloWorld.vue";
</script>

<template>
  <img
    alt="Vue logo"
    src="../assets/logo.png"
    class="
      relative
      left-3.5rem
      inline
      transform
      ease-linear
      duration-4000
      -rotate-1800
      hover:(opacity-10
      ease-linear
      duration-4000
      translate-x-35rem
      rotate-1800
      )
    "
  />
  <img
    class="
      relative
      right-6.2rem
      -z-1
      inline
      mx-auto
      max-w-full
      w-auto
      max-h-120px
      block
      select-none
    "
    src="../assets/logo.svg"
    alt="Windi CSS logo"
  />
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite + WindiCSS"></HelloWorld>
</template>

<script lang="ts">
// @ is an alias to /src

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
