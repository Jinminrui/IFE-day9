<template>
  <section class="section1">
    <div class="content-wrapper">
      <div class="small-title">BOATLOADS OF AWESOME</div>
      <div class="big-title">Ready-made, customizable, HTML landing page sections</div>
      <div class="list">
        <div class="line">
          <div class="item">
            <div class="icon"><img src="./Iphone-Icon.png"></div>
            <div class="text">
              <h3>Mobile First</h3>
              <p>All modulz are built mobile-first for maximum device compatibility.</p>
            </div>
          </div>
          <div class="item">
            <div class="icon"><img src="./Check-Icon.png"></div>
            <div class="text">
              <h3>Accessibility</h3>
              <p>Support for IE8, mobile and tablet devices, screenreaders and color blind.</p>
            </div>
          </div>
        </div>
        <div class="line">
          <div class="item">
            <div class="icon"><img src="./Pencil-Icon.png"></div>
            <div class="text">
              <h3>Fluid Typography</h3>
              <p>On different screen sizes, fonts automagically scale with the viewport.</p>
            </div>
          </div>
          <div class="item">
            <div class="icon"><img src="./Settings-Icon.png"></div>
            <div class="text">
              <h3>Customization</h3>
              <p>Make any design your own using the Style Editor. Personalize fonts, colors, and layouts to create the custom look you want.</p>
            </div>
          </div>
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
section
  display flex
  justify-content center
  padding 88px 0
  .content-wrapper
    text-align center
    display flex
    flex-direction column
    align-items center
    .small-title
      font-size 14px
      margin-bottom 40px
    .big-title
      width 770px
      line-height 50px
      font-size 42px
      margin-bottom 60px
    .list
      .line
        display flex
        justify-content space-around
      .item
        display flex
        height 90px
        width 450px
        margin-right 220px
        margin-bottom 86px
        &:last-child
          margin-right 0
        .icon
          img
            width 40px
        .text
          flex 1
          margin-left 38px
          text-align left
          h3
            margin-bottom 24px
            font-size 20px
          p
            font-size 16px
            line-height 26px
            color rgba(129, 129, 129, 0.64)
</style>
