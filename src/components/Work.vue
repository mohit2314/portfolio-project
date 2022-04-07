<template>
  <section class="work section" id="work">
      <span class="section__subtitle">
          My Portfolio
      </span>
      <h2 class="section__title">Recent Works</h2>
<!-- TODO: Load work as per filter selected with animation -->
      <div class="work__filters">
<span class="work__item active-work">All</span>
<span class="work__item">Web</span>
<span class="work__item">Mobile</span>
<span class="work__item">Design</span>
      </div>

      <div class="work__container container grid">
          <div class="work__card" v-for="(card,index) in workCards" :key="index">
              <img :src="require(`../assets/img/${card.img}`)" alt="" class="work__img">
              <h3 class="work__title">{{card.title}}</h3>
              <a href="#" class="work__button">
                  Demo
                  <i class="bx bx-right-arrow-alt work__icon"></i>
              </a>
          </div>
      </div>
  </section>
</template>

<script>
export default {
data(){
    return{
        workCards:[
            {
               title:'Web Design',
               img: 'work1.jpg'
            },
            {
               title:'Mobile App',
               img: 'work2.jpg'

            },
            {
               title:'Brand Design',
               img: 'work3.jpg'

            },
            {
               title:'App Devlopment',
               img: 'work4.jpg'

            },
            {
               title:'App Devlopment',
               img: 'work5.jpg'

            },
        ]
    }
}
}
</script>

<style>

</style>