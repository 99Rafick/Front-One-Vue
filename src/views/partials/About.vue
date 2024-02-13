<script setup>
import SectionTitle from "@/components/SectionTitle.vue";
import PrimaryButton from "@/components/PrimaryButton.vue";
</script>
<template>
    <section id="about" class="w-full relative mt-5 lg:w-[96%] grid lg:grid-cols-2 mx-auto lg:h-screen">
        <div class="lg:py-16 lg:px-10">
            <SectionTitle
                class="w-10/12"
                sub-title="about us"
                title="The team will turn your ideas into reality"
            />
            <p class="mt-5 w-10/12">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci aliquid asperiores, commodi deleniti deserunt earum fuga ipsam iure magnam maxime molestias mollitia nisi obcaecati officiis porro provident.</p>

            <PrimaryButton class="mt-7" name="More About us" link="#" />

            <div class="mt-12 w-full lg:h-64 lg:gap-y-5 rounded-2xl border grid lg:grid-cols-2 lg:p-10">
                <div class="text-center">
                    <h4 class="text-4xl">8</h4>
                    <p>Operated Years</p>
                </div>
                <div class="text-center">
                    <h4 class="text-4xl">200+</h4>
                    <p>Happy Clients</p>
                </div>
                <div class="text-center">
                    <h4 class="text-4xl">40+</h4>
                    <p>Professionals</p>
                </div>
                <div class="text-center">
                    <h4 class="text-4xl">650+</h4>
                    <p>Amazing Project</p>
                </div>
            </div>
        </div>
        <img class="lg:h-screen w-full object-cover rounded-2xl" src="https://i.pinimg.com/originals/d9/4b/64/d94b64da451a7857da5162ace2b645ce.jpg" alt="">
    </section>
</template>
