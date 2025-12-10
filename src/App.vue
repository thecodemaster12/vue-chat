<script setup>
import DarkToggle from './components/DarkToggle.vue';
import Nav from './components/Nav.vue';

</script>
 
<template>
  <main>
    <DarkToggle />
    <div class="bg-emerald-400 min-h-screen flex">
      <Nav />
      <div class="bg-yellow-500 flex-1">Content</div>
    </div>
  </main>
</template>