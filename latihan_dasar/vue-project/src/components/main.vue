
<script setup>
defineProps({
    name: {
        type: String,
        required: true
    }
})
</script>
<template>
    <h1>HelloWorld</h1>
    <h2>{{ name }}</h2>
    <button>klik</button>
    <h3>sahddhasd</h3>
</template>
<style scoped>
button {
    padding: 10px;
    width: 100px;
    border-radius: 10px;
    border: 1px solid whitesmoke;
    margin: 10px;
}

button:hover {
    background-color: rgb(10, 242, 10);
}
</style>