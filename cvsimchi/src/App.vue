<template>
<div>
  <headerSite />
  <sliderSite />
  <aboutSite />
  <contactSite />
</div>
</template>

<script>
import headerSite from './components/headerSite.vue' 
import sliderSite from './components/sliderSite.vue' 
import aboutSite from './components/aboutSite.vue' 
import contactSite from './components/contactSite.vue' 
export default {
  name: 'App',
  components : {headerSite,
   sliderSite,
    aboutSite,  
    contactSite,}
}
</script>
