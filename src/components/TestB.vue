<script setup>
import TestC from './TestC.vue';
defineProps({
    test: {
        type: String,
        default: 'b'
    }
})

</script>

<template>
    <TestC :test="test" />
</template>