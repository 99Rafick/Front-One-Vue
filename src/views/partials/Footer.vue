<script setup>
import SectionTitle from "@/components/SectionTitle.vue";
import TertiaryButton from "@/components/TertiaryButton.vue";
</script>

<template>
    <footer class="lg:mt-24 lg:w-[96%] lg:py-10 lg:flex lg:flex-col lg:justify-between lg:rounded-3xl lg:pt-28 bg-black lg:min-h-[90vh] mx-auto">
        <div>
          <SectionTitle
              sub-title="contact us"
              title="You've got this far. Ready to get started?"
              :color-white="true"
              class="lg:w-4/12 mx-auto text-center"
          />
          <TertiaryButton class="mx-auto lg:mt-8" link="#" name="Get in touch" />
        </div>
        <div class="w-full h-max lg:px-10">
              <div class="w-full flex lg:h-24 border-b-2 border-white/30 items-center justify-between">
                  <h3 class="lg:text-2xl text-white">Reemax</h3>
                  <ul class="flex text-sm text-white/50 items-center gap-10">
                    <li><a href="#">Accueil</a></li>
                    <li><a href="#">Service</a></li>
                    <li><a href="#">Avis</a></li>
                    <li><a href="#">Plan</a></li>
                    <li><a href="#">Faq</a></li>
                  </ul>
                  <div class="space-x-10">
                    <a href="#">
                      <ion-icon class="text-white text-lg" name="logo-facebook"></ion-icon>
                    </a>
                    <a href="#">
                      <ion-icon class="text-white text-lg" name="logo-twitter"></ion-icon>
                    </a>
                    <a href="#">
                      <ion-icon class="text-white text-lg" name="logo-medium"></ion-icon>
                    </a>
                  </div>
              </div>
              <div class="flex items-center text-white/50 lg:mt-5 text-xs lg:justify-between">
                    <div>
                        Copyright 2022 Reemax, Inc. All right reserved.
                    </div>
                    <div>
                      <a href="#">Privacy Policy</a>
                      <a href="#">FAQ</a>
                      <a href="#">Terms of service</a>
                    </div>
              </div>
        </div>
    </footer>
</template>
