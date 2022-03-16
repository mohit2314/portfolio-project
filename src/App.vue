<template>
<div id="app">
  <router-view/>  
</div>
</template>

<script>
import Header from '@/components/Header.vue';
import "./assets/css/globalStyles.css";

export default {
  components:{
    Header
  }
  
}
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap');

</style>
