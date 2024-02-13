<template>
  <nav class="navbar">
    <ul class="navbar-nav">
      <li>
        <router-link to="/" class="nav-link">Home</router-link>
      </li>
      <li>
        <router-link to="/about" class="nav-link">About</router-link>
      </li>
      <!-- Ajoute d'autres éléments de navigation ici -->
    </ul>
  </nav>
</template>

<script lang="ts">
/* eslint-disable */
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Navbar'
})
</script>

<style>
.navbar {
  background-color: #333;
  overflow: hidden;
}

.navbar-nav {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  align-items: center;
}

.nav-link {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.nav-link:hover {
  background-color: #555;
}
</style>
