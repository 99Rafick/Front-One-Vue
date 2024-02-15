<script setup>

import Header from "@/views/partials/Header.vue";
import HeroBanner from "@/views/partials/HeroBanner.vue";
import Sponsors from "@/views/partials/Sponsors.vue";
import Works from "@/views/partials/Works.vue";
import Services from "@/views/partials/Services.vue";
import About from "@/views/partials/About.vue";
import Testimonials from "@/views/partials/Testimonials.vue";
import Footer from "@/views/partials/Footer.vue";
</script>

<template>
    <Header />
    <main>
        <HeroBanner />
        <Sponsors />
        <Works />
        <Services />
        <About />
        <Testimonials />
    </main>
    <Footer />
</template>
