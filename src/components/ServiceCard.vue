<script setup>
    import IconRightButton from "@/components/IconRightButton.vue";

    defineProps({
        image: String,
        link: String,
        title: String,
        subTitle: String,
    })
</script>

<template>
    <div class="flex-none relative h-max">
        <img :src="image" class="w-full h-96 rounded-2xl" alt="Image" />
        <div class="w-full lg:mt-5 flex items-center justify-between">
            <div>
              <h3 class="lg:text-2xl">{{title}}</h3>
              <span class="text-sm lg:mt-3">{{subTitle}}</span>
            </div>
            <IconRightButton :link="link" />
        </div>
    </div>
</template>