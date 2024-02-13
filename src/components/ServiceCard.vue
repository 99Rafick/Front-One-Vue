<script setup>
import InfoButton from "@/components/InfoButton.vue";

defineProps({
    title: String,
    text: String,
    link: String,
    image: String,
})
</script>

<template>
    <div class="grid relative lg:grid-cols-2 lg:gap-28">
        <div class="bg-white/10 relative flex items-center justify-center rounded-xl w-full h-80">
          <img class="h-64 object-cover" :src="image" alt="image"/>
        </div>
        <div class="flex flex-col justify-center">
            <h3 class="text-white text-2xl">{{title}}</h3>
            <p class="mt-3 text-white/50">{{text}}</p>
            <InfoButton class="lg:mt-10" name="Learn more" :link="link" />
        </div>
    </div>
</template>
