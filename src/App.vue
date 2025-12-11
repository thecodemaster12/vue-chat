<script setup>
import ChatBox from './components/ChatBox.vue';
import Nav from './components/Nav.vue';
</script>
 
<template>
  <main>
    <div class="bg-emerald-400 min-h-screen flex">
      <Nav />
      <div class="bg-gray-600 flex-1">
        <Chat  Box />
      </div>
    </div>
  </main>
</template>