<script setup>
 defineProps({
    link: String,
    name: String,
 })

</script>


<template>
  <a :href="link" class="button-size bg-blue-500/10 text-blue-500">{{ name }}</a>
</template>