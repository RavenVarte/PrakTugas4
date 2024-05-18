<template>
    <h1>
      {{ title || 'Tidak ada pesan' }}
    </h1>
  </template>
  
  <script setup>
  defineProps({
    title: String,
  })
  </script>