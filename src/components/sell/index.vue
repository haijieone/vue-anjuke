<template>
  <div class="sellinfo">
    <div class="lists">
      <h1 class="question">我在惠州买了2套红本房现在贷款中 出售后打算买深圳红本 可以贷款吗？</h1>
      <p class="answer">卖掉一套，可在深圳买一套做贷款，前提要么深户，要么社保连续五年，要不然只有买公寓了。我深圳，惠州房子都做</p>
      <div class="question_content">
        <span class="span1">61回答</span>
        <span class="span2">|</span>
        <span class="span3">2019-07-06</span>
        <span class="span4">二手房</span>
        <span class="span5">中介</span>
        <span class="span6">中介费</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.lists {
  height: 1.06rem;
  display: flex;
  flex-direction: column;
  padding: 0.15rem 0.15rem 0.15rem;
  border-bottom: 1px solid #ccc;
  .question {
    height: 0.24rem;
    font-size: 0.17rem;
    color: #333;
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  .answer {
    height: 0.21rem;
    color: #999999;
    font-size: 0.14rem;
    margin: 0.04rem 0 0;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  .question_content {
    width: 100%;
    display: flex;
    height: 0.14rem;
    margin: 0.08rem 0 0.15rem;
  }
  .span1,
  .span2,
  .span3 {
    display: inline-block;
    color: #999999;
    font-size: 0.12rem;
    display: flex;
  }
  .span2,
  .span3 {
    padding-left: 0.06rem;
  }

  .span4,
  .span5,
  .span6 {
    display: inline-block;
    color: #8099af;
    font-size: 0.12rem;
    padding-left: 0.06rem;
  }
}
</style>