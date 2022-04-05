<template>
<Header />
<MainSection />
<About />
<Skills />
<Services />
<Work />
</template>

<script >
import Header from '@/components/Header.vue';
import MainSection from '@/components/MainSection.vue';
import About from '@/components/About.vue'
// import main from '@/views/main'
import Skills from '@/components/Skills.vue';
import Services from '@/components/Services.vue';
import Work from '@/components/Work.vue';
export default {
 components:{
   Header,
   MainSection,
   About,
   Skills,
   Services,
   Work
 }

};
</script>
