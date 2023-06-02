<template>
  <div class="BACKGROUND">
    <q-layout>
      <q-header class="bg-transparent">
        <HeaderPage />
      </q-header>

      <q-page-container>
        <q-page>
          <ContentPage />
        </q-page>
      </q-page-container>

      <q-footer class="bg-transparent q-mb-md column items-center">
        <FooterPage />
      </q-footer>
    </q-layout>
  </div>
</template>

<script setup>
import HeaderPage from "../components/HeaderPage.vue";
import ContentPage from "../components/ContentPage.vue";
import FooterPage from "../components/FooterPage.vue";
</script>
<style scoped>
.BACKGROUND {
  background: linear-gradient(68.15deg, #0a141e, #1f4d6e 85.61%);
}
</style>
