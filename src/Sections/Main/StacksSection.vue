<script setup>
import Stack from '@/MyComponents/StackComp.vue'
import SectionLayout from '@/Layouts/SectionLayout.vue';
import Wrapper from '@/MyComponents/FlexWrapper.vue'
</script>
<template>
    <SectionLayout >
        <template #header>
            Stacks
        </template>
        <template #desc>
            Descriptions 
        </template>
        <Wrapper>
            <Stack :stack="{'name': 'Inertia JS', 'level':80}"/>
            <Stack :stack="{'name': 'Laravel', 'level':80}"/>
            <Stack :stack="{'name': 'HTML', 'level':80}"/>
            <Stack :stack="{'name': 'CSS', 'level':80}"/>
            <Stack :stack="{'name': 'Javacript', 'level':80}"/>
            <Stack :stack="{'name': 'Django', 'level':80}"/>
            <Stack :stack="{'name': 'Python', 'level':80}"/>
            <Stack :stack="{'name': 'Vue JS', 'level':80}"/>
            <Stack :stack="{'name': 'PHP', 'level':80}"/>            
        </Wrapper>
    </SectionLayout>
    
</template>
<style scoped>
</style>