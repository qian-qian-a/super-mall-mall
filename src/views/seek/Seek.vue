<template>
  <div>
    <div>
      <nav-bar class="seek-nav"><div slot="center">查询</div></nav-bar>
      <seek-main/>
      <seek-recommend/>
    </div>
  </div>
</template>

<script>
  import NavBar from 'components/common/navbar/NavBar.vue'
  import SeekMain from './childComps/SeekMain.vue'
  import SeekRecommend from './childComps/SeekRecommend.vue'

  export default {
    name: "Seek",
    components: {
      NavBar,
      SeekMain,
      SeekRecommend
    }
  }
</script>

<style scoped>
 
  .seek-nav {
    background-color: var(--color-tint);
    color: #fff;
  }
</style>
