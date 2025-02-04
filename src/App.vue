<template>
    <div class="flex flex-col min-h-screen bg-app-primary">
        <nav-bar></nav-bar>
        <router-view></router-view>
    </div>
</template>

<script setup>
import NavBar from "./components/NavBar.vue";
import { RouterView } from "vue-router";
</script>
