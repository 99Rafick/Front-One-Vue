<script setup>
import SecondaryButton from "@/components/SecondaryButton.vue";
import IconRightButton from "@/components/IconRightButton.vue";
import SectionTitle from "@/components/SectionTitle.vue";
</script>
<template>
    <section id="hero-banner">
        <div class="hero-banner-left lg:p-16 relative flex items-end" style="background-image: url('https://images.pexels.com/photos/2569997/pexels-photo-2569997.jpeg'); background-size: cover">
            <div class="flex items-center justify-between">
              <SectionTitle
                  :color-white="true"
                  class="w-8/12"
                  sub-title="SOFTWARE DEVELOPPEMENT SERVICE"
                  title="We are website & app  development agency"
              />
              <SecondaryButton class="flex-none" name="Get in touch" link="#" />
            </div>
        </div>
        <div class="hero-banner-right overflow-hidden">
            <img class="h-96 rounded-3xl object-cover w-full" src="https://images.pexels.com/photos/5240140/pexels-photo-5240140.jpeg" alt="Image">
            <div class="flex mt-5 items-center justify-between">
              <div class="">
                <span class="text-extrasmall uppercase text-gray-500 font-light">OUR LATEST WORK</span>
                <h2 class="w-8/12 text-smallbig">FastBank</h2>
              </div>
              <IconRightButton class="flex-none" link="#" />
            </div>
        </div>
    </section>
</template>
