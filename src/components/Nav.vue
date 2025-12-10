<script setup>
import { HugeiconsIcon } from '@hugeicons/vue';
import { Home03Icon } from '@hugeicons/core-free-icons';
</script>

<template>
    <nav class="bg-white dark:bg-black w-20 py-4">
        <div class="flex flex-col items-center gap-4">
            <a href="">
                <HugeiconsIcon class="text-black dark:text-white" :icon="Home03Icon" :size="26" :stroke-width="1.5" />
            </a>
            <a href="">
                <HugeiconsIcon class="text-black dark:text-white" :icon="Home03Icon" :size="26" :stroke-width="1.5" />
            </a>
            <a href="">
                <HugeiconsIcon class="text-black dark:text-white" :icon="Home03Icon" :size="26" :stroke-width="1.5" />
            </a>
        </div>
    </nav>
</template>

<style scoped></style>