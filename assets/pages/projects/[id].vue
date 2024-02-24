<script setup lang="ts">
import { ref } from 'vue';
import { useRoute } from 'vue-router';

const route = useRoute()

const id = ref(route.params.id)
</script>

<template>
  <main>
    Project Name {{ id }}
  </main>
</template>
