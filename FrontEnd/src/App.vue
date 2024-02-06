<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <section>
    <div class="header">
      <RouterLink to="/">Overtime</RouterLink>
      <div class="header-right">
        <RouterLink to="/about">About</RouterLink>
        <div class="dropdown">
        <RouterLink to="/about">User</RouterLink>
        </div>
      </div>
    </div>
  </section>
  <RouterView />
</template>

<style scoped>
.header {
  font-family:'revamped';
  font-size: 40px;
  width: 99%;
  background-color: #292726;
  padding: 0px 20px 0px 0px;
}
.header-right {
  float: right;
  color: rgb(189, 132, 0);
}
.dropdown{
  float: right;
}
a,
.orange {
  text-decoration: none;
  color: rgb(189, 132, 0);
  transition: 0.4s;
  padding: 3px;
  text-align: center;
  text-decoration: none;
  border-radius: 4px;
}
@media (hover: hover) {
  a:hover {
    background-color: hsla(37, 80%, 27%, 0.2);
  }
}
</style>
