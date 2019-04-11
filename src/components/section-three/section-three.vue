<template>
  <section class="section3">
    <div class="content-wrapper">
      <h1 class="title">Try Our Awesome Products</h1>
      <div class="list">
        <div class="item">
          <div class="icon"><img src="./Singleton.png"></div>
          <div class="text">Li Jun, a China Academy of Engineering academician and also director of the alliance's experts' committee, said that China will also launch design guidance for smart cars, smart map architecture and standards for test grounds.</div>
        </div>
        <div class="item">
          <div class="icon"><img src="./Hero.png"></div>
          <div class="text">Li said the smart car industry is able to enlarge the current car industry by 1 trillion yuan ($158.15 billion) and also able to boost fast development in 5G, internet of cars, big data, artificial intelligence and new-energy vehicles.</div>
        </div>
        <div class="item">
          <div class="icon"><img src="./Portland.png"></div>
          <div class="text">Zhang Junyi, a partner with NIO Capital, said that the smart car is the trend for the car industry and China's auto sector will usher in a new key development stage with the improvement of infrastructure, technology, policies and laws.</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script type="text/ecmascript-6">
export default {
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
.section3
  width 100%
  border-bottom 1px solid #dddddd
  .content-wrapper
    display flex
    flex-direction column
    align-items center
    justify-content center
    margin 100px 0
    .title
      font-size 42px
      margin-bottom 80px
    .list
      display flex
      justify-content space-around
      .item
        margin-right 60px
        .icon
          text-align center
          margin-bottom 20px
        .text
          width 300px
          font-size 16px
          text-align center
          color #666666
          line-height 26px
</style>
