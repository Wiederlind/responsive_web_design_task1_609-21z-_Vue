<script setup>
import VHeader from '@/components/VHeader.vue'
import VPromo from '@/components/VPromo.vue'
import VProjects from '@/components/VProjects.vue'
import VTech from '@/components/VTech.vue'
import VFeedback from '@/components/VFeedback.vue'
import VFooter from '@/components/VFooter.vue'
</script>

<template>
    <v-header />
    <main>
        <v-promo />
        <v-projects />
        <v-tech />
        <v-feedback />
    </main>
    <v-footer />
</template>

<style scoped>
</style>
