<script setup>
defineProps({
  link: String,
  name: String,
})

</script>


<template>
  <a :href="link" class="button-size bg-white text-blue-500">{{ name }}</a>
</template>