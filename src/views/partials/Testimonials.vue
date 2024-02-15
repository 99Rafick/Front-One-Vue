<script setup>
import SectionTitle from "@/components/SectionTitle.vue";
import SecondaryButton from "@/components/SecondaryButton.vue";
</script>
<template>
    <section id="testimonials" class="sections-spacing padding lg:py-5">
        <SectionTitle
          sub-title="testimonials"
          title="What they say about us"
        />

        <div class="grid lg:grid-cols-4 lg:gap-10 lg:mt-10">
            <div class="col-span-3 lg:h-[470px] w-full border lg:flex lg:flex-col lg:justify-between overflow-hidden border-gray-200 rounded-3xl">
                <p class="lg:p-16 lg:w-11/12 text-black font-normal lg:text-3xl lg:leading-[3rem]">
                   "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Animi aspernatur debitis dicta eaque esse, eum magni modi, necessitatibus non obcaecati praesentium."
                </p>
                <div class="lg:h-32 border-t bg-gray-100 flex items-center justify-between lg:px-16">
                      <div class="flex items-center gap-5">
                          <img src="https://images.pexels.com/photos/415829/pexels-photo-415829.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="image" class="h-14 w-14 rounded-full flex-none object-cover">
                          <div>
                              <h6 class="text-xl font-medium">Aaron mario, CEO</h6>
                              <p class="flex items-center gap-2">
                                  <span class="p-0.5 font-bold text-xs flex items-center justify-center flex-none text-black rounded-full border border-black" ><ion-icon name="star"></ion-icon></span>
                                  <span class="text-black font-bold">We-famous</span>
                              </p>
                          </div>
                      </div>
                      <div class="flex items-center gap-5">
                          <button class="w-14 h-14 rounded-full border border-gray-200 bg-white flex items-center justify-center">
                            <ion-icon class="text-2xl" name="chevron-back-outline"></ion-icon>
                          </button>
                          <button class="w-14 h-14 rounded-full border border-gray-200 bg-white flex items-center justify-center">
                            <ion-icon class="text-2xl" name="chevron-forward-outline"></ion-icon>
                          </button>
                      </div>
                </div>
            </div>
            <div class="bg-blue-600 relative rounded-3xl lg:flex lg:flex-col lg:items-center lg:justify-between lg:py-16">
                  <img class="h-20 object-cover" src="/img/techny-calculator-and-notepad-with-mathematics-signs.png" alt="image">
                  <div class="w-full lg:flex lg:flex-col lg:gap-5 lg:items-center">
                      <h5 class="lg:text-3xl lg:text-center lg:w-10/12 text-white font-bold">Want to estimate your project ?</h5>
                      <SecondaryButton name="Project estimation" link="#" />
                  </div>
            </div>
        </div>
    </section>
</template>
