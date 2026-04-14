Remi Kalkan
14/04/2026


<script setup>
import HelloWorld from './components/HelloWorld.vue'
const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
const today = new Date().toLocaleDateString('fr-FR')
</script>

<template>
  <header>
    <p>Nom : Remi Kalkan</p>
    <p>Date : {{ today }}</p>
    <p>Build : {{ buildId }}</p>
  </header>
</template>
