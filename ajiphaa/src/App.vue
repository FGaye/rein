<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper p-3 border-bottom  border-1 border-secondary  ">
      <nav>
        <RouterLink to="/" class="link">Home</RouterLink>
        <RouterLink to="/goodies" class="link">Goodies</RouterLink>
      </nav>
    </div>
  </header>
  <RouterView />
</template>

<style scoped>
 
  nav{
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 50px;
    
  }
  .link{
    color: #050505;
    text-decoration: none;
  }
</style>
