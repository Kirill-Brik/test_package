<script setup>
defineProps({
    test: {
        type: String,
        default: 'c'
    }
})
</script>

<template>
    <div class="test-c">
        test c {{ test }}
    </div>
</template>