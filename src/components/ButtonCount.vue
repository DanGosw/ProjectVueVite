<script setup>

import { ref } from 'vue';
const cont = ref(0)
const counter = () => cont.value++
</script>

<template>

    <button @click="counter">
        {{ cont }}
    </button>
</template>

<style scoped>

</style>