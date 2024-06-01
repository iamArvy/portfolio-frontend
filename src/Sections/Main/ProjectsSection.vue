<script setup>
import Project from '@/MyComponents/ProjectComp.vue'
import Wrapper from '@/MyComponents/FlexWrapper.vue'
import SectionLayout from '@/Layouts/SectionLayout.vue';
</script>
<template id="projects">
    <SectionLayout >
        <template #header>
            Projects
        </template>
        <template #desc>
            Descriptions 
        </template>
        <Wrapper>
            <Project :project="{'img': '', 'name': '', 'about': '', 'stacks': '', 'url' : '', 'git':' '}" />
        </Wrapper>
    </SectionLayout>
    
</template>
<style scoped>
</style>