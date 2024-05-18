<template>

    <Title :title="greeting" />
    <Title title="Haloo Data" />
<emit />
</template>

<script setup>
import { ref } from 'vue'
const greeting = ref ('Pesan ini Parent')
import emit from './EmitBut.vue'
</script>