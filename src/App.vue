<script setup>
import { PktBackLink } from "@oslokommune/punkt-vue";
</script>

<template>
  <header>
    <img
      alt="Vue logo"
      class="logo"
      src="./assets/logo.svg"
      width="125"
      height="125"
    />
  </header>

  <main>
    <PktBackLink href="http://localhost:5173" text="Gå tilbake" />
    <section>Masse bra innhold.</section>
  </main>
</template>
<style scoped lang="scss">
@use "@pkt/scss/abstracts/variables" with (
  $font-path: "@oslokommune/punkt-assets/dist/fonts"
);
@use "@pkt/scss/pkt";
</style>
