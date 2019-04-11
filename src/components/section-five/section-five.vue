<template>
  <section class="section5">
    <div class="content-wrapper">
      <h1 class="title">Our Awesome Crew</h1>
      <p class="desc">Our unique online teaching style makes learning easy for everyone. Whether you are trying to land a new job, brush up on your skills.</p>
      <div class="list">
        <div class="row">
          <div class="item">
            <div class="img-wrapper"><img src="./1.png"></div>
            <div class="info-wrapper">
              <div class="name">Ethan Dutton</div>
              <div class="intro">Senior Visual Designer</div>
              <div class="icon-list">
                <div class="icon"><img src="./Facebook-Icon.png"></div>
                <div class="icon"><img src="./Twitter-Icon.png"></div>
                <div class="icon"><img src="./Instagram-Icon.png"></div>
              </div>
            </div>
          </div>
          <div class="item">
            <div class="img-wrapper"><img src="./2.png"></div>
            <div class="info-wrapper">
              <div class="name">Ethan Dutton</div>
              <div class="intro">Senior Visual Designer</div>
              <div class="icon-list">
                <div class="icon"><img src="./Facebook-Icon.png"></div>
                <div class="icon"><img src="./Twitter-Icon.png"></div>
                <div class="icon"><img src="./Instagram-Icon.png"></div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="item">
            <div class="img-wrapper"><img src="./3.png"></div>
            <div class="info-wrapper">
              <div class="name">Ethan Dutton</div>
              <div class="intro">Senior Visual Designer</div>
              <div class="icon-list">
                <div class="icon"><img src="./Facebook-Icon.png"></div>
                <div class="icon"><img src="./Twitter-Icon.png"></div>
                <div class="icon"><img src="./Instagram-Icon.png"></div>
              </div>
            </div>
          </div>
          <div class="item">
            <div class="img-wrapper"><img src="./4.png"></div>
            <div class="info-wrapper">
              <div class="name">Ethan Dutton</div>
              <div class="intro">Senior Visual Designer</div>
              <div class="icon-list">
                <div class="icon"><img src="./Facebook-Icon.png"></div>
                <div class="icon"><img src="./Twitter-Icon.png"></div>
                <div class="icon"><img src="./Instagram-Icon.png"></div>
              </div>
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
.section5
  width 100%
  display flex
  justify-content center
  border-bottom 1px solid #dddddd
  .content-wrapper
    display flex
    flex-direction column
    align-items center
    text-align center
    margin-top 96px
    margin-bottom 68px
    .title
      font-size 42px
    .desc
      font-size 18px
      width 708px
      line-height 26px
      color #666666
      margin-bottom 68px
    .list
      .row
        display flex
        justify-content space-between
        margin-bottom 30px
        .item
          position relative
          margin-right 50px
          &:last-child
            margin-right 0
          .img-wrapper
            img
              width 470px
              height 340px
          .info-wrapper
            display flex
            flex-direction column
            justify-content center
            align-items center
            position absolute
            top 0
            left 0
            height 100%
            width 100%
            background rgba(22, 22, 22, 0.6)
            opacity 0
            transition opacity 0.25s ease-in-out
            cursor pointer
            &:hover
              opacity 1
          .name
            font-size 20px
            color white
            margin-bottom 20px
          .intro
            font-size 12px
            color #999999
            margin-bottom 30px
            text-transform uppercase
          .icon-list
            display flex
            justify-content center
            align-items center
            .icon
              display flex
              justify-content center
              align-items center
              margin-right 30px
              width 40px
              height 40px
              border 1px solid #999999
              border-radius 50%
              &:last-child
                margin-right 0
</style>
