<script setup>

import VHeader from "@/components/VHeader.vue";
import VFooter from "@/components/VFooter.vue";
import VPromo from "@/components/VPromo.vue";
import VFeedback from "@/components/VFeedback.vue";
import VCards from "@/components/VCards.vue";
import VResponce from "@/components/VResponce.vue";
</script>

<template>
  <v-header />
  <main>
    <v-promo />
    <v-cards />
    <v-responce />
    <v-feedback />
  </main>
  <v-footer />
</template>

<style scoped>

</style>
