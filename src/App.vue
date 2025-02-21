<template>
    <div class="flex flex-col container min-h-screen font-audio-wide bg-app-primary">
        <nav-bar></nav-bar>
        <router-view></router-view>
    </div>
</template>

<script setup>
import NavBar from "./components/NavBar.vue";
import { RouterView } from "vue-router";
</script>
