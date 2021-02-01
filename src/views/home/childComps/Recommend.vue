<template>
  <div class="recommend">
    <recommend-view class="recommend-item">
      <a href="">
        <img src="~assets/img/home/recommend/recommend4.png" alt="">
        <div>快递服务</div>
      </a>
    </recommend-view>
    <recommend-view class="recommend-item">
      <a href="">
        <img src="~assets/img/home/recommend/recommend1.png" alt="">
        <div>物流查询</div>
      </a>
    </recommend-view>
    <recommend-view class="recommend-item">
      <a href="">
        <img src="~assets/img/home/recommend/recommend3.png" alt="">
        <div>信息掌握</div>
      </a>
    </recommend-view>
    <recommend-view class="recommend-item">
      <a href="">
        <img src="~assets/img/home/recommend/recommend2.png" alt="">
        <div>快人一步</div>
      </a>
    </recommend-view>
  </div>
</template>

<script>
import RecommendView from 'components/common/recommend/RecommendView.vue'

export default {
  name: "Recommend",
  components: {
    RecommendView
  }
}
</script>

<style>
  .recommend {
    display: flex;
    width: 100%;
    text-align: center;
    font-size: 12px;

    padding: 10px 0 10px;
    border-bottom: 8px solid #eee;
    /* background-color: seagreen; */
  }

  .recommend-item {
    flex: 1;
    /* background-color: rgb(163, 119, 61); */
  }

  .recommend-item img {
    width: 70px;
    height: 90px;
    margin-bottom: 2px;
  }
</style>