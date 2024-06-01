<template>
    <SectionLayout>
        <template #header>
            About Me
        </template>
        <div >
            <Info />
        </div>
        <Certification />

    </SectionLayout>
</template>
<script setup>
    import SectionLayout from '@/Layouts/SectionLayout.vue';
    import Certification from '@/Partials/About/CertificationPart.vue';
    import Info from '@/Partials/About/InfoPart.vue';
</script>
<style scoped>

</style>