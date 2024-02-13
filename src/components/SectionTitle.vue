<script setup>
    import {computed} from "vue";

    const props = defineProps({
        subTitle: String,
        title: String,
        colorWhite: {
            type: Boolean,
            default: false,
        }
    })

    const getTextClasses = computed(() => {
      return {
        'text-extrasmall': true,
        'uppercase': true,
        'font-light': true,
        'text-gray-300': props.colorWhite,
        'text-gray-400': !props.colorWhite,
      };
    });

    const getTitleClasses = computed(() => {
      return {
        'mt-5': true,
        'text-big': true,
        'text-white': props.colorWhite,
      };
    });
</script>
<template>
  <div>
    <span :class="getTextClasses">{{ subTitle }}</span>
    <h2 :class="getTitleClasses">{{ title }}</h2>
  </div>
</template>