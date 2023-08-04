<script setup>
const props = defineProps({
    time: String
})
</script>

<template>
    <span class="timestamp">{{ time }}</span>
</template>

<style>
</style>