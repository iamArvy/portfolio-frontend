<template>
    <MainLayout title="Home">
        <div id="hero">
            <Hero/>
        </div>
        <div id="about" class="plus">
            <About />
        </div>
        <div id="stack" class="plus">
            <Stack/>
        </div>
        <div id="projects" class="plus">
            <Project/>
        </div>
        <div id="contact" class="plus">
            <Contact/>
        </div>
    </MainLayout>
</template>
<style scoped>
    .plus{
        padding-top: 70px;
    }
</style>
<script setup>
import MainLayout from '@/Layouts/MainLayout.vue';
import Hero from '@/Sections/Main/HeroSection.vue';
import About from '@/Sections/Main/AboutSection.vue';
// import Project from '@/Sections/Main/ProjectsSection.vue';
import Stack from '@/Sections/Main/StacksSection.vue';
// import Contact from '@/Sections/Main/ContactSection.vue'
// import { defineProps, onMounted } from 'vue';
</script>