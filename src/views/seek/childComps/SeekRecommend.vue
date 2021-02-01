<template>
  <div class="seekrecommend">
    <recommend-view class="recommend-item">
      <a href="http://www.sto.cn/home/index">
        <img src="~assets/img/seek/shentong.png" alt="">
        <div>申通快递</div>
      </a>
    </recommend-view>
    <recommend-view class="recommend-item">
      <a href="https://www.sf-express.com/cn/sc/">
        <img src="~assets/img/seek/shunfeng.png" alt="">
        <div>顺丰速运</div>
      </a>
    </recommend-view>
    <recommend-view class="recommend-item">
      <a href="http://www.yundaex.com/cn/index.php">
        <img src="~assets/img/seek/yunda.png" alt="">
        <div>韵达速递</div>
      </a>
    </recommend-view>
    <recommend-view class="recommend-item">
      <a href="https://www.so.com/link?m=bko%2F4jPEjsKIAtvRcE1VBi3qB04%2Bt%2BnP7ANe4OevlzoeAmRSOM%2FnNai0f%2FmPIP1TkDOC4wPiFOK9Exd8%2FSuJybVdkXpgreh1UvYlgXGEySv1zi9jpCeSsBJBpOak%3D">
        <img src="~assets/img/seek/yuantong.png" alt="">
        <div>圆通速递</div>
      </a>
    </recommend-view>
  </div>
</template>

<script>
  import RecommendView from 'components/common/recommend/RecommendView.vue'

  export default {
    name: "SeekRecommend",
    components: {
      RecommendView
    }
  }
</script>

<style>
  .seekrecommend {
    display: flex;
    width: 100%;
    text-align: center;
    font-size: 12px;

    padding: 10px 0 10px;
    /* border-bottom: 8px solid #eee; */
  }
  .recommend-item {
    flex: 1;
  }

  .recommend-item img {
    width: 70px;
    height: 70px;
    margin-bottom: 2px;
  }
</style>