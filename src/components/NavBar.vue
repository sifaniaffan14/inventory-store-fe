<template>
  <nav class="navbar">
    <router-link to="/" class="nav-item">Login</router-link>
    <router-link to="/dashboard" class="nav-item">Dashboard</router-link>
  </nav>
</template>

<script setup lang="ts"></script>

<style scoped>
.navbar {
  display: flex;
  gap: 1rem;
  background-color: #42b983;
  padding: 0.5rem 1rem;
}
.nav-item {
  color: white;
  text-decoration: none;
}
.nav-item.router-link-active {
  font-weight: bold;
}
</style>