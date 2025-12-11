<script setup>
import { HugeiconsIcon } from '@hugeicons/vue';
import { Home03Icon,Settings01Icon, Logout05Icon, Notification01FreeIcons } from '@hugeicons/core-free-icons';
import DarkToggle from './DarkToggle.vue';
</script>

<template>
    <nav class="bg-white dark:bg-black w-20 py-8">
        <div class="flex flex-col justify-between h-full">
            <div class="flex flex-col items-center gap-6">
                <a href="">
                    <HugeiconsIcon class="text-black dark:text-white" :icon="Home03Icon" :size="26"
                        :stroke-width="1.5" />
                </a>
                <a href="">
                    <HugeiconsIcon class="text-black dark:text-white" :icon="Notification01FreeIcons" :size="26"
                        :stroke-width="1.5" />
                </a>
                <DarkToggle />
            </div>
            <div class="flex flex-col items-center gap-6">
                <a href="">
                    <HugeiconsIcon class="text-black dark:text-white" :icon="Settings01Icon" :size="26"
                        :stroke-width="1.5" />
                </a>
                <a href="">
                    <HugeiconsIcon class="text-black dark:text-white" :icon="Logout05Icon" :size="26"
                        :stroke-width="1.5" />
                </a>
            </div>
        </div>

    </nav>
</template>

<style scoped></style>