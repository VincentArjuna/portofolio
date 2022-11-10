<script setup>
import { Head } from "@inertiajs/inertia-vue3";
import FrontendLayout from "@/Layouts/FrontendLayout.vue";
import Hero from "@/Components/Frontend/Hero.vue";
import Promote from "@/Components/Frontend/Promote.vue";
import About from "@/Components/Frontend/About.vue";
import Skills from "@/Components/Frontend/Skills.vue";
import Portofolio from '@/Components/Frontend/Portofolio.vue';
import Services from '@/Components/Frontend/Services.vue';
import ContactMe from '@/Components/Frontend/ContactMe.vue';

defineProps({
    skills: Object,
    projects: Object
});

</script>

<template>

    <Head title="Welcome to VAWM" />
    <FrontendLayout>
        <!-- Hero primary-->
        <Hero />
        <!-- Promote tail 100 -->
        <Promote />
        <!-- About secondary -->
        <About />
        <!-- Skills tail 100 -->
        <Skills :skills="skills" />
        <!-- Portofolio -->
        <Portofolio :skills="skills" :projects="projects" />
        <!-- Services secondary-->
        <Services />
        <!-- Contact primary-->
        <ContactMe />
    </FrontendLayout>
</template>
