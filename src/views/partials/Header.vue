<script setup>
   import PrimaryButton from "@/components/PrimaryButton.vue";
</script>
<template>
  <header>
      <div>
          <h1 id="title">Reemax</h1>
          <nav>
            <ul class="flex items-center gap-10">
              <li><a href="#">Accueil</a></li>
              <li><a href="#">Service</a></li>
              <li><a href="#">Avis</a></li>
              <li><a href="#">Plan</a></li>
              <li><a href="#">Faq</a></li>
            </ul>
          </nav>
      </div>

      <PrimaryButton name="Project estimation" link="#" />
  </header>
</template>
