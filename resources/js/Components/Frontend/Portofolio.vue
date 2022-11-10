<script setup>
import Projects from '@/Components/Frontend/Projects.vue';

defineProps({
    skills: Object,
    projects: Object
});
</script>

<template>
    <section id="portofolio" class="section bg-light-primary dark:bg-dark-primary min-h-[1400px]">
        <div class="container mx-auto" v-motion :initial="{ opacity: 0, y: 100, }" :visible="{ opacity: 1, y: 0, }">
            <div class="flex flex-col items-center text-center">
                <h2 class="section-title">My Latest Work</h2>
                <p class="subtitle">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum venenatis ornare lacus non
                    rutrum. Quisque nec volutpat elit. Pellentesque habitant morbi tristique senectus et netus et
                    malesuada fames ac turpis egestas.
                </p>
            </div>
        </div>
        <Projects :skills="skills" :projects="projects" />
    </section>
</template>