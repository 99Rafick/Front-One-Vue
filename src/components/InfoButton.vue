<script setup>
defineProps({
  link: String,
  name: String,
})

</script>
<template>
  <a :href="link" class="button-size bg-white/10 text-white">{{ name }}</a>
</template>