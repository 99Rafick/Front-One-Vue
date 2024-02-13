<script setup>
import SectionTitle from "@/components/SectionTitle.vue";
import PrimaryButton from "@/components/PrimaryButton.vue";
import ServiceCard from "@/components/ServiceCard.vue";
</script>

<template>
    <section id="services" class="padding sections-spacing">
        <div class="flex items-start w-full justify-between">
            <SectionTitle
                class="w-6/12"
                sub-title="our work"
                title="We help business to make their product come to life, worldwide."
            />

            <div class="w-4/12 mt-12 space-y-5">
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet earum possimus qui sequi. Accusantium at cum dolor eius.</p>
              <PrimaryButton name="See all works" link="#" />
            </div>
        </div>

        <div class="sections-spacing w-full overflow-x-scroll flex gap-10">
          <ServiceCard
              class="w-[calc(50%-40px)]"
              link="#"
              image="https://images.pexels.com/photos/38568/apple-imac-ipad-workplace-38568.jpeg"
              title="Bloomey, housplants store"
              sub-title="Website Development"
          />
          <ServiceCard
              class="w-[calc(50%-40px)]"
              link="#"
              image="https://images.pexels.com/photos/285814/pexels-photo-285814.jpeg"
              title="Bloomey, housplants store"
              sub-title="Website Development"
          />
          <ServiceCard
              class="w-[calc(50%-40px)]"
              link="#"
              image="https://images.pexels.com/photos/38568/apple-imac-ipad-workplace-38568.jpeg"
              title="Bloomey, housplants store"
              sub-title="Website Development"
          />
          <ServiceCard
              class="w-[calc(50%-40px)]"
              link="#"
              image="https://images.pexels.com/photos/285814/pexels-photo-285814.jpeg"
              title="Bloomey, housplants store"
              sub-title="Website Development"
          />
          <ServiceCard
              class="w-[calc(50%-40px)]"
              link="#"
              image="https://images.pexels.com/photos/38568/apple-imac-ipad-workplace-38568.jpeg"
              title="Bloomey, housplants store"
              sub-title="Website Development"
          />
          <ServiceCard
              class="w-[calc(50%-40px)]"
              link="#"
              image="https://images.pexels.com/photos/285814/pexels-photo-285814.jpeg"
              title="Bloomey, housplants store"
              sub-title="Website Development"
          />
        </div>
    </section>
</template>
