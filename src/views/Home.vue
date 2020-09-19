<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenShayna />
    <InstaShayna />
    <SupportShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/Home/HeroShayna.vue';
import WomenShayna from '@/components/Home/WomenShayna.vue';
import InstaShayna from '@/components/Home/InstaShayna.vue';
import SupportShayna from '@/components/Home/SupportShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';


export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenShayna,
    InstaShayna,
    SupportShayna,
    FooterShayna
  }
}
</script>
