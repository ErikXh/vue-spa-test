<script setup>

import NavBar from "./components/NavBar.vue";
import CostumHeader from "./components/CostumHeader.vue";
import HomeSection from "./components/HomeSection.vue";
import MiniSection from "./components/MiniSection.vue";
import Functionality from "./components/Functionality.vue";
import DemoVid from "./components/DemoVid.vue";
import Screenshots from "./components/Screenshots.vue";
import TeamSection from "./components/TeamSection.vue";
import Reviews from "./components/Reviews.vue";
import PricingSection from "./components/PricingSection.vue";
import FAQSection from "./components/FAQSection.vue";
import DownloadSection from "./components/DownloadSection.vue";
import BlogSection from "./components/BlogSection.vue";
import FooterSection from "./components/FooterSection.vue";
</script>

<template>
  <CostumHeader>
    <NavBar></NavBar>
    <HomeSection></HomeSection>
  </CostumHeader>
  <MiniSection></MiniSection>
  <Functionality></Functionality>
  <DemoVid></DemoVid>
  <Screenshots></Screenshots>
  <TeamSection></TeamSection>
  <Reviews></Reviews>
  <PricingSection></PricingSection>
  <FAQSection></FAQSection>
  <DownloadSection></DownloadSection>
  <BlogSection></BlogSection>
  <FooterSection></FooterSection>
</template>

<style>
</style>
