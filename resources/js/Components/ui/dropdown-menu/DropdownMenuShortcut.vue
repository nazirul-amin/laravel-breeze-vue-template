<script setup>
import { cn } from '@/Utils';

const props = defineProps({
  class: { type: null, required: false },
});
</script>

<template>
  <span :class="cn('ml-auto text-xs tracking-widest opacity-60', props.class)">
    <slot />
  </span>
</template>
