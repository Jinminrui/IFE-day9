<template>
  <header>
    <div class="content-wrapper">
      <h1>Hello World</h1>
      <p>China is speeding up strategic plan, standards, traffic rules, laws and regulations on accident-incurred liabilities for its smart car industry, Economic Information Daily reported Thursday.</p>
      <div class="form-wrapper">
        <div class="title">CREATE YOUR ACCOUNT</div>
        <div class="sub">IT IS ABSOLUTELY FREE</div>
        <div class="form">
          <input placeholder="denis@getcraftwork.com">
          <input placeholder="Create your password">
          <button>SIGN UP</button>
        </div>
      </div>
    </div>
  </header>
</template>

<script type="text/ecmascript-6">
export default {
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
header
  width 100%
  background url('bg-header.png') no-repeat
  background-size cover
  position relative
  z-index 0
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
    text-align center
    padding 210px 0
    display flex
    justify-content center
    flex-direction column
    align-items center
    h1
      font-size 62px
      color white
      font-weight 300
      margin-bottom 86px
    p
      width 766px
      font-size 19px
      line-height 25px
      font-weight 100
      color rgba(255, 255, 255, 0.6)
      margin-bottom 105px
    .form-wrapper
      padding 51px 41px
      border 1px solid rgb(129, 129, 129)
      .title
        font-size 18px
        color white
        margin-bottom 20px
      .sub
        font-size 12px
        color rgba(129, 129, 129, 0.64)
        margin-bottom 46px
      .form
        input
          width 290px
          height 50px
          margin-right 30px
          padding-left 18px
          background-color transparent
          border 1px solid rgb(129, 129, 129)
        button
          position relative
          width 125px
          height 52px
          border none
</style>
