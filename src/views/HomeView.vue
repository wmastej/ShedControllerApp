<template>
    <main class="container text-white">
        <div class="flex flex-nowrap pt-4 mb8 relative">
            <div class="size-15 grow"></div>
            <div class="size-15 grow">
                <input
                    type="text"
                    v-model="searchQuery"
                    placeholder="Search for something"
                    class="py-2 px-1 w-full bg-transparent border-b focus:border-app-secondary focus:outline-none focus:shadow-[0px-1px_0_0_#004E71]"
                />{{ searchQuery }}
            </div>
            <div class="size-15 grow"></div>
        </div>
    </main>
</template>

<script setup>
import { ref } from "vue";

const searchQuery = ref("");

</script>
