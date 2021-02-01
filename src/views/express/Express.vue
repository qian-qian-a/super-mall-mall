<template>
  <div class="wrapper">
    <nav-bar class="express-nav"><div slot="center">寄快递</div></nav-bar>
    <input-message/>
  </div>
</template>

<script src="assets/js/layui.all.js"></script>
<script>
  import NavBar from 'components/common/navbar/NavBar.vue'
  import InputMessage from './childComps/InputMessage'

  export default {
    name: "Express",
    components: {
      NavBar,
      InputMessage
    }
  }
</script>

<style scoped>
 .express-nav {
   background-color: var(--color-tint);
    color: #fff;
 }
</style>
