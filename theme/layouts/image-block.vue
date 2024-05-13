<script setup lang="ts">
const props = defineProps({
  image: {
    type: String,
    required: true,
  },
  alt: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="slidev-layout image-block">
    <slot />
    <img :src="image" :alt="alt" />
  </div>
</template>
