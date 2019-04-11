<template>
  <section class="section2">
    <div class="content-wrapper">
      <div class="left">
        <div class="title">Supportive policies for China's smart car</div>
        <div class="desc">China will come up with its own smart car standards, traffic rules, laws and regulations relating to safety, according to the China Industry Innovation Alliance for the Intelligent and Connected Vehicles.</div>
        <div class="button-wrapper">
          <button>Check out Features</button>
          <button>Try product for Free</button>
        </div>
      </div>
      <div class="right">
        <div class="ipad">
          <img src="./IPad.png">
          <img
            class="screen"
            src="./Screen.png"
          >
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
.section2
  position relative
  background url('bg.png') no-repeat
  background-size cover
  z-index 0
  width 100%
  &::after
    content ''
    display block
    position absolute
    top 0
    left 0
    width 100%
    height 100%
    background-color rgba(20, 20, 20, 0.65)
    z-index -1
  .content-wrapper
    width 100%
    display flex
    justify-content space-between
    .left
      margin-left 300px
      margin-top 180px
      .title
        font-size 42px
        line-height 50px
        color white
        width 430px
        margin-bottom 100px
      .desc
        font-size 18px
        color #dddddd
        line-height 26px
        width 430px
        margin-bottom 58px
      .button-wrapper
        display flex
        margin-bottom 182px
        button
          width 240px
          height 60px
          border none
          margin-right 30px
          text-transform uppercase
          &:last-child
            margin-right 0
            background transparent
            border 1px solid rgb(129, 129, 129)
            color white
    .right
      display flex
      align-items center
      .ipad
        position relative
        .screen
          position absolute
          right 0
          top 50%
          transform translateY(-50%)
</style>
