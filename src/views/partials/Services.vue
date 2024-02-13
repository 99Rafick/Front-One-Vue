<script setup>
import SectionTitle from "@/components/SectionTitle.vue";
import ServiceCard from "@/components/ServiceCard.vue";
</script>

<template>
    <section id="services" class="sections-spacing lg:w-[96%] lg:py-16 rounded-2xl mx-auto bg-black lg:min-h-screen">
          <SectionTitle
            class="w-1/2 flex flex-col items-center mx-auto text-center"
            sub-title="our service"
            title="We help businesses to make their product come to life, worldwide"
            :color-white="true"
          />

          <div class="lg:mt-20 lg:space-y-16" >
              <ServiceCard
                  image="/img/techny-web-design.png"
                  class="w-9/12 mx-auto"
                  title="Website development"
                  text="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad consectetur corporis dolores ea, eos harum hic incidunt ipsa laudantium, maxime nesciunt nobis."
              />

              <ServiceCard
                  image="/img/techny-data-science-on-laptop-screen.png"
                  class="w-9/12 mx-auto"
                  title="Web app development"
                  text="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad consectetur corporis dolores ea, eos harum hic incidunt ipsa laudantium, maxime nesciunt nobis."
              />

              <ServiceCard
                  image="/img/techny-mobile-app-development-and-web-development.png"
                  class="w-9/12 mx-auto"
                  title="Mobile app development"
                  text="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad consectetur corporis dolores ea, eos harum hic incidunt ipsa laudantium, maxime nesciunt nobis."
              />
          </div>

    </section>
</template>
