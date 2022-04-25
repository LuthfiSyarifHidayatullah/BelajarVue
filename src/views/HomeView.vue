<template>
  <div class="home">
    <header-shayna />
   <hero-section />
   <women-shayna/>
   <insta-shayna/>
   <partner-shayna/>
   <footer-shayna/>
    


  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroSection from '@/components/HeroSection.vue'
import WomenShayna from '@/components/WomenShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'



export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroSection ,
    WomenShayna , 
    InstaShayna ,
    PartnerShayna,
    FooterShayna
    
  }
}
</script>
