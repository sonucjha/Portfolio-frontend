<template>
  <!-- header 
   ================================================== -->
  <header>
    <div class="row">
      <!-- <top-menu></top-menu> -->

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

  <!-- FAMILY Section
   ================================================== -->
   <family-detail></family-detail>
  <!-- /cta -->

  <!-- services Section
   ================================================== -->
   <service-menu></service-menu>
  <!-- /services -->

  <!-- stats Section
   ================================================== -->
  <business-type></business-type>
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
import FamilyDetail from "./MyFamily.vue"
import FooterMenu from "./MyFooter.vue"
import PortfolioMenu from "./MyPortfolio.vue"
import ResumeMenu from "./MyResume.vue"
import SectionMenu from "./MySection.vue"
import ServiceMenu from "./MyService.vue"
import BusinessType from "./BusinessType.vue"
</script>
