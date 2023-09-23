<template>
  <!-- header 
   ================================================== -->
  <header>
    <div class="row">
      <top-menu></top-menu>
      <!-- /top-bar -->
    </div>
    <!-- /row -->
  </header>
  <!-- /header -->

  <!-- intro section
   ================================================== -->
    <intro-menu></intro-menu>
  <!-- /intro -->

  <!-- about section
   ================================================== -->
    <section-menu></section-menu>
  <!-- /process-->

  <!-- resume Section
   ================================================== -->
  <resume-menu></resume-menu>
  <!-- /features -->

  <!-- Portfolio Section
   ================================================== -->
    <portfolio-menu></portfolio-menu>
  <!-- /portfolio -->

  <!-- CTA Section
   ================================================== -->
   <cta-menu></cta-menu>
  <!-- /cta -->

  <!-- services Section
   ================================================== -->
   <service-menu></service-menu>
  <!-- /services -->

  <!-- stats Section
   ================================================== -->
  <status-menu></status-menu>
  <!-- /stats -->

  <!-- contact
   ================================================== -->
  <contact-Menu></contact-Menu>
  <!-- /contact -->

  <!-- footer
   ================================================== -->

 <footer-menu></footer-menu>
  <div id="preloader">
    <div id="loader"></div>
  </div>
</template>
<script setup>
import TopMenu from "./TopMenu.vue";
import IntroMenu from "./MyIntro.vue"
import ContactMenu from "./MyContact.vue"
import CtaMenu from "./MyCta.vue"
import FooterMenu from "./MyFooter.vue"
import PortfolioMenu from "./MyPortfolio.vue"
import ResumeMenu from "./MyResume.vue"
import SectionMenu from "./MySection.vue"
import ServiceMenu from "./MyService.vue"
import StatusMenu from "./MyStatus.vue"
</script>
