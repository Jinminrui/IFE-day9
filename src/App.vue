<template>
  <div id="app">
    <m-header></m-header>
    <section-one></section-one>
    <section-two></section-two>
    <section-three></section-three>
    <section-four></section-four>
    <section-five></section-five>
    <section-six></section-six>
    <m-footer></m-footer>
  </div>
</template>

<script>
import MHeader from '@/components/m-header/m-header'
import SectionOne from '@/components/section-one/section-one'
import SectionTwo from '@/components/section-two/section-two'
import SectionThree from '@/components/section-three/section-three'
import SectionFour from '@/components/section-four/section-four'
import SectionFive from '@/components/section-five/section-five'
import SectionSix from '@/components/section-six/section-six'
import MFooter from '@/components/m-footer/m-footer'
export default {
  name: 'app',
  components: {
    MHeader,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive,
    SectionSix,
    MFooter
  }
}
</script>
<style lang="stylus"></style>
