<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <h2 class="logo"><RouterLink to="/">Overtime</RouterLink></h2>
    <nav class="navigation">
      <RouterLink to="/about">About </RouterLink>
      <RouterLink to="/about">News </RouterLink>
      <button class="btnLogin-popup"><RouterLink to="/Login" class="login">Login</RouterLink></button>
    </nav>
  </header>
  <RouterView />
</template>
