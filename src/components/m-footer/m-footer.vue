<template>
  <footer>
    <div class="content-wrapper">
      <div class="link-list">
        <div class="title">Learn More</div>
        <a href="#">How it works?</a>
        <a href="#">Meeting tools</a>
        <a href="#">Live streaming</a>
        <a href="#">Contact method</a>
      </div>
      <div class="link-list">
        <div class="title">About us</div>
        <a href="#">About us</a>
        <a href="#">Features</a>
        <a href="#">Privacy police</a>
        <a href="#">Terms & Conditions</a>
      </div>
      <div class="link-list">
        <div class="title">support</div>
        <a href="#">F A Q</a>
        <a href="#">Contact us</a>
        <a href="#">Live chat</a>
        <a href="#">Phone call</a>
      </div>
      <div class="link-list">
        <div class="title">enjoy your life</div>
        <p>Great web UI kit for designers, freelancers or business.</p>
        <div class="icons">
          <img src="./Twitter-Icon.png">
          <img src="./Facebook-Icon.png">
          <img src="./Google-Icon.png">
          <img src="./Tumbler-Icon.png">
          <img src="./Pinterest-Icon.png">
          <img src="./LinkedIn-Icon.png">
        </div>
      </div>
    </div>
  </footer>
</template>

<script type="text/ecmascript-6">
export default {
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
footer
  width 100%
  height 411px
  background rgb(20, 20, 20)
  .content-wrapper
    display flex
    justify-content space-around
    margin-left 144px
    margin-right 144px
    .link-list
      display flex
      flex-direction column
      justify-content space-between
      margin-top 88px
      font-size 16px
      &:last-child
        justify-content flex-start
      .title
        text-transform uppercase
        color white
        margin-bottom 36px
      a
        display block
        color #888888
        text-decoration none
        margin-bottom 36px
      p
        width 300px
        font-size 18px
        line-height 26px
        color #888888
        margin-bottom 30px
      .icons
        display flex
        justify-content space-between
</style>
