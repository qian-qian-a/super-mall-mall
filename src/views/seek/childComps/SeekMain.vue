<template>
  <div class="seekmain">
    <img src="~assets/img/seek/main0.jpg" alt="">
    <div class="board">
      <span v-if="isexpressseek">
        <!-- <label for="express">运单号</label> -->
        <input type="text" id="express" placeholder="请输入运单号" key="express">
      </span>
      <span v-else>
        <!-- <label for="phone">电话号码</label> -->
        <input type="text" id="phone" placeholder="请输入电话号码" key="phone">
      </span>
      <button @click="change">切换类型</button>
      
      <button>马上查单</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "SeekMain",
  data() {
    return {
      isexpressseek: true
    }
    
  },
  methods: {
    change(){
			this.isexpressseek=!this.isexpressseek
		}
  }
}
</script>

<style>
 .seekmain {
    width: 100%;
    height: 100%;
    background-image: url(~assets/img/seek/main0.jpg);
    /* background-attachment: fixed; */
  } 
  .seekmain img{
    width: 100%;
  }
  .board {
    width: 46%;
    height: 14%;
    position: absolute; 
    background-color: rgb(238, 229, 229);
    top: 15%;
    left: 2%;
    border-radius: 10%;
  }
  .board input {
    width: 90%;
    height: 28%;
    border-radius: 10%;
    border-color: var(--color-tint);
    background-color: rgba(112, 107, 107, 0.2);
    position: relative;
    top: 10%;
    left: 5%;
    /* size: 14px; */
  }
  .board button {
    width: 90%;
    height: 28%;
    border-radius: 10%;
    border-color: var(--color-tint);
    background-color: rgba(199, 31, 87, 0.4);
    position: relative;
    top: 12%;
    left: 5%;
    color: #005555;
  }
</style>