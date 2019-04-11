<template>
  <section class="section6">
    <div class="content-wrapper">
      <div class="form-wrapper">
        <div class="title">Fell free to Write Us</div>
        <input
          type="text"
          placeholder="E-mail"
        >
        <input
          type="text"
          placeholder="Subject"
        >
        <textarea placeholder="Message"></textarea>
        <button>SEND</button>
      </div>
      <div class="info-wrapper">
        <div class="title">Contacts</div>
        <div class="desc">Make any design your own using the Style Editor. Personalize fonts, colors, and layouts to create the custom look you want.</div>
        <div class="contact">
          <div class="item">
            <div class="icon"><img src="./Map-Icon.png"></div>
            <div class="text">360 King Street<br>
              Feastrvale Trevose, PA 19057 </div>
          </div>
          <div class="item">
            <div class="icon"><img src="./Phone-Icon.png"></div>
            <div class="text">(755) 564-84-12</div>
          </div>
          <div class="item">
            <div class="icon"><img src="./Mail-Icon.png"></div>
            <div class="text">youname@mail.com</div>
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
.section6
  width 100%
  display flex
  justify-content center
  .content-wrapper
    display flex
    justify-content space-between
    margin-bottom 50px
    .form-wrapper
      display flex
      flex-direction column
      align-items center
      margin-top 70px
      padding 0 50px
      padding-bottom 50px
      border 1px solid #dddddd
      .title
        text-align center
        margin 50px 0
        font-size 16px
        text-transform uppercase
      input
        display block
        margin-bottom 30px
        padding-left 10px
        width 370px
        height 50px
      textarea
        padding-left 10px
        width 370px
        height 200px
        border 1px solid #dddddd
        resize none
        margin-bottom 30px
      button
        box-sizing content-box
        width 370px
        height 52px
        background #222222
        color white
        border none
    .info-wrapper
      margin-left 130px
      margin-top 160px
      width 400px
      .title
        font-size 42px
        font-weight 500
        margin-bottom 36px
      .desc
        font-size 16px
        line-height 28px
        color #666666
        margin-bottom 75px
      .contact
        .item
          display flex
          justify-content center
          align-items center
          margin-bottom 30px
          .icon
            margin-right 12px
          .text
            flex 1
            font-size 16px
            line-height 20px
</style>
