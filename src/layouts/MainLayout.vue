<template>
  <div>
    <TheHeader />

    <main>
      <slot />
    </main>

    <TheFooter />
  </div>
</template>

<script setup lang="ts">
import TheHeader from '@/components/TheHeader.vue'
import TheFooter from '@/components/TheFooter.vue'
defineOptions({
  name: 'MainLayout',
})
</script>
