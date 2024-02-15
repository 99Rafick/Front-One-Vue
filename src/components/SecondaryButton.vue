<script setup>
defineProps({
  link: String,
  name: String,
  colorText: {
      type: Boolean,
      default: false,
  }
})

</script>
<template>
  <a :href="link" :class="['button-size bg-white', {'text-blue-500': colorText}]">{{ name }}</a>
</template>