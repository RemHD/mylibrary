<template>
  <nav class="flex bg-gray-200 items-center px-4">
    <div class="flex items-center space-x-4">
      <img src="./../assets/logo-no-background.svg" width="32" height="32" alt="logo" />
      <router-link to="/" class="text-gray-800 hover:text-gray-600">Home</router-link>
      <router-link to="/about" class="text-gray-800 hover:text-gray-600">About</router-link>
    </div>
  </nav>
</template>

<script lang="ts">
/* eslint-disable */
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Navbar'
})
</script>
