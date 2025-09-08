<template>
  <div class="title-section text-left text-sm-center poppins-font">
    <h2>{{ props.title.split(" ")[0] }} <span>{{ props.title.split(" ")[1] }}</span>
    </h2>
    <span class="title-bg">{{ props.subtitle }}</span>
  </div>
</template>
<script setup lang="ts">
const props = defineProps<{
  title: string
  subtitle: string
}>()
</script>