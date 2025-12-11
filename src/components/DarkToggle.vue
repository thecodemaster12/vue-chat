<script setup>
import { HugeiconsIcon } from '@hugeicons/vue'
import { Sun02Icon, Moon02Icon } from '@hugeicons/core-free-icons'
import { ref, onMounted } from 'vue'

const isDark = ref(false)

onMounted(() => {
  if (localStorage.getItem('theme') === 'dark') {
    isDark.value = true
    document.documentElement.classList.add('dark')
  }
})

const toggleTheme = () => {
  isDark.value = !isDark.value

  if (isDark.value) {
    document.documentElement.classList.add('dark')
    localStorage.setItem('theme', 'dark')
  } else {
    document.documentElement.classList.remove('dark')
    localStorage.setItem('theme', 'light')
  }
}
</script>

<template>
  <button
    @click="toggleTheme"
    class="dark:text-white cursor-pointer"
  >
  <HugeiconsIcon :icon="isDark ? Sun02Icon : Moon02Icon" :size="26" :stroke-width="1.5" />
  </button>
</template>
