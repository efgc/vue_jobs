<script setup>
import Hero from '@/components/Hero.vue';
import HomeCards from '@/components/HomeCards.vue';
import JobListings from '@/components/JobListings.vue';

</script>

<template>
    <Hero />
    <HomeCards />
    <JobListings :limit=9 :showButton="true" />
    <h1 class="text-3xl">abc</h1>
</template>