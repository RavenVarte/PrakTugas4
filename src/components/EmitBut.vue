<template>
    <br>
    <button @click="ubahTeks">click me</button> <br><br>
</template>

<script setup>
const emit = defineEmits(['response'])

function ubahTeks() {
    emit('response', 'hello from child')
}

</script>