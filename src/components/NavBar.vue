<template>
    <header class="grid grid-cols-1 sticky top-0 bg-app-primary shadow-lg">
        <nav class="container flex flex-col sm:flex-row items-center gap-4 text-white py-6">
            <RouterLink v-bind:to="{ name: 'home'}">
                <div class="flex items-center gap-3">
                    <p class=" text-2xl">Shed Controller App</p>
                </div>
            </RouterLink>
            <div class="flex gap-3 flex-1 justify-end">
                III
            </div>
        </nav>
    </header>
</template>

<script setup>
import { RouterLink } from 'vue-router';
</script>
