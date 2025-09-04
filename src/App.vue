<template>
  <WebHeader />
  <WebHero />
  <WebAbout />
  <WebServices />   
  <WebPortfolio />
  <WebTestimonial/>
  <WebContact/>
  <WebFooter/>
</template>

<script>

import WebHeader from './components/WebHeader.vue';
import WebHero from './components/WebHero.vue';
import WebAbout from './components/WebAbout.vue';
import WebServices from './components/WebServices.vue';
import WebPortfolio from './components/WebPortfolio.vue';
import WebTestimonial from './components/WebTestimonial.vue';
import WebContact from './components/WebContact.vue';
import WebFooter from './components/WebFooter.vue';

export default {
  name: 'App',
  components: {
    WebHeader,
    WebHero,
    WebAbout,
    WebServices,
    WebPortfolio,
    WebTestimonial,
    WebContact,
    WebFooter,
  
  }
}
</script>

<style>
/* Smooth scroll for internal anchor links */
html {
  scroll-behavior: smooth;
}

/* Make sure main container fits screen */
#app {
  max-width: 100%;
  overflow-x: hidden;
}
/* Link styling with transition */
a {
  position: relative;
  display: inline-block;
  padding: 5px 10px;
  text-decoration: none;
  transition: color 0.3s ease;
}

/* Hover underline animation */
a::after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  width: 0%;
  height: 2px;
  background: #2563eb; /* Tailwind "primary-600" like blue */
  transition: width 0.3s ease;
}

a:hover {
  color: #2563eb; /* matches primary-600 */
}

a:hover::after {
  width: 100%;
}

</style>
