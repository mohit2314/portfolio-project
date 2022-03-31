<template>
<Header />
<MainSection />
<About />
</template>

<script >
import Header from '@/components/Header.vue';
import MainSection from '@/components/MainSection.vue';
import About from '@/components/About.vue'
// import main from '@/views/main'
export default {
 components:{
   Header,
   MainSection,
   About
 }

};
</script>
