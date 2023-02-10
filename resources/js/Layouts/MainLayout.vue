<template>
    <div class="text-gray-900 text-sm font-sans">
        <Navigation />
        <slot />
    </div>
</template>

<script setup lang="ts">
import Navigation from '@/Components/Navigation.vue'
</script>