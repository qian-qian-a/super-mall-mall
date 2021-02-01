<template>
  <div id="home" class="wrapper">
    <nav-bar class="home-nav"><div slot="center">首页</div></nav-bar>
    <home-swiper />
    <recommend/>
  </div>
</template>

<script>
  import HomeSwiper from './childComps/HomeSwiper'
  import NavBar from 'components/common/navbar/NavBar'
  import Recommend from './childComps/Recommend'

  export default {
    name: "Home",
    components: {
      HomeSwiper,
      NavBar,
      Recommend
    }
  }
</script>

<style scoped>
  #home {
    padding-top: 44px;
    /* height: 100vh;
    position: relative; */
  }
  .home-nav {
    /* assets/css/base.css 设置了主题色 */
    background-color: var(--color-tint);
    color: #fff;

    position: fixed;
    left: 0;
    right: 0;
    top: 0;
    z-index: 9;
  }

</style>
