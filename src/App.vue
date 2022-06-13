<script setup>
import { RouterLink, RouterView } from "vue-router";
import Navbar from "@/components/Navbar.vue";
import Presentation from "@/components/Presentation.vue";
import Features from "@/components/Features.vue";
import Preview from "@/components/Preview.vue";
import Download from "@/components/Download.vue";
import About from "@/components/About.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <Navbar />
  <Presentation />
  <div class="container">
    <Features />
    <br />
    <Preview />
    <br />
    <Download />
    <br />
    <About />
  </div>
  <Footer />
</template>

<style>
@import "@/assets/base.css";

.container {
  margin: 0 auto;
  padding: 2rem;
  max-width: 1280px;
  font-weight: normal;
}

a {
  transition: all 0.2s ease-out;
}

a:hover {
  background: #171717;
}
</style>
