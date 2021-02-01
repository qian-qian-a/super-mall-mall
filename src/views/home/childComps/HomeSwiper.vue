<template>
  <swiper>
    <swiper-item>
      <a href="">
        <img src="~assets/img/home/swiper/swiper1.png" alt="" @load="imageLoad">
      </a>
    </swiper-item>
    <swiper-item>
      <a href="">
        <img src="~assets/img/home/swiper/swiper2.png" alt="" @load="imageLoad">
      </a>
    </swiper-item>
    <swiper-item>
      <a href="">
        <img src="~assets/img/home/swiper/swiper3.png" alt="" @load="imageLoad">
      </a>
    </swiper-item>
    <swiper-item>
      <a href="">
        <img src="~assets/img/home/swiper/swiper4.png" alt="" @load="imageLoad">
      </a>
    </swiper-item>
  </swiper>
</template>

<script>
  import {Swiper, SwiperItem} from 'components/common/swiper'

  export default {
    name: "HomeSwiper",
    components: {
      Swiper,
      SwiperItem
    },
    methods: {
    }
  }
</script>

<style scoped>

</style>
