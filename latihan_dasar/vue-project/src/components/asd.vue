

<script setup>
defineProps({
    nama: {
        type: String,
        required: true
    }
})
</script>
<template>
    <h1>test ajaa gtu</h1>
    <h2>data</h2>
    <h3>{{nama}}</h3>
</template>

<style scoped>
h1{font-size: 100px;}
</style>