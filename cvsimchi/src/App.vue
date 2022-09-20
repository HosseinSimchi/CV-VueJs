<template>
<div>
  <headerSite />
  <sliderSite />
  <aboutSite />
  <experienceSite />
  <workSite />
  <contactSite />
  <footerSite />
</div>
</template>

<script>
import headerSite from './components/headerSite.vue' 
import sliderSite from './components/sliderSite.vue' 
import aboutSite from './components/aboutSite.vue' 
import experienceSite from './components/experienceSite.vue' 
import workSite from './components/workSite.vue' 
import contactSite from './components/contactSite.vue' 
import footerSite from './components/footerSite.vue' 
export default {
  name: 'App',
  components : {headerSite,
   sliderSite,
    aboutSite, 
    experienceSite, 
    workSite, 
    contactSite,
    footerSite}
}
</script>
