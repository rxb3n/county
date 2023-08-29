<template>
  <NavView/>
  <HeroView/>
  <AboutView/>
  <DescriptionView/>
  <LocationView/>
  <CtaView/>
  <FooterView/>
</template>

<script>
import NavView from './components/NavView.vue'
import HeroView from './components/HeroView.vue'
import AboutView from './components/AboutView.vue'
import DescriptionView from './components/DescriptionView.vue'
import LocationView from './components/LocationView.vue'
import CtaView from './components/CtaView.vue'
import FooterView from './components/FooterView.vue'

export default {
  name: 'App',
  components: {
    NavView,
    HeroView,
    AboutView,
    DescriptionView,
    LocationView,
    CtaView,
    FooterView,
  }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Glass+Antiqua&family=Roboto:wght@400;500;700&display=swap');

:root {
  --background-color: #1D4E89;
  --button-secondary: #00B2CA;
  --font-family-primary:'Roboto', sans-serif;
  --font-family-secondary: 'Glass Antiqua', cursive;
  --font-color-primary: #7DCFB6;
  --font-color-secondary: #FBD1A2;
}


body {
  margin: 0;
  padding: 0;
  background-color: var(--background-color);
  overflow-x: hidden;
}

h1, h2, h3, h4, h5, h6 {
  margin: 0;
  padding: 0;
}

</style>
