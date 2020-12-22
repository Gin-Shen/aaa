<template lang = 'pug'>
.image
.line1
.line2
.w1title {{w1text}}
.w2title {{w2text}}
.w3title {{w3text}}
.w4title {{w4text}}
.w5title {{w5text}}
.w6title {{w6text}}
.w7title {{w7text}}

<div class="home">
  <img alt="Vue logo" src="../assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  data(){
    return{
      //字的命名
      w1text: '國立清華大學 藝術學院',
      w2text: 'ＨＯＭＥ',
      w3text: '最新消息',
      w4text: '學士班',
      w5text: '科藝賞析',
      w6text: '招生',
      w7text: '師資',
    }
  }
}
</script>
<style lang = 'sass'>
.image
  position: absolute
  width: 1050px
  height: 767px
  left: 104px
  top: 116px
  background-size: cover
  background: url(../assets/nthu.jpg)
.line1
  position: absolute
  width: 1395px
  height: 0px
  left: 20px
  top: 84px
  border: 1px solid #9A8C98
.line2
  position: absolute
  width: 1395px
  height: 0px
  left: 20px
  top: 951px
  border: 1px solid #9A8C98

.w1title
  position: absolute
  width: 477px
  height: 31px
  left: 58px
  top: 44px
  font-family: Roboto
  font-style: normal
  font-weight: normal
  font-size: 30px
  line-height: 25px
  /* or 83% */
  letter-spacing: 0.3em
  color: #9A8C98

.w2title
  position: absolute
  width: 216px
  height: 84px
  left: 575px
  top: 32px
  font-family: Roboto
  font-style: normal
  font-weight: normal
  font-size: 30px
  line-height: 50px
  letter-spacing: 0.25em
  color: #9A8C98

.w3title
  position: absolute
  width: 249px
  height: 44px
  left: 878px
  top: 30px
  font-family: Roboto
  font-style: normal
  font-weight: normal
  font-size: 30px
  line-height: 50px
  /* or 167% */
  letter-spacing: 0.3em
  color: #9A8C98

.w4title
  position: absolute
  width: 209px
  height: 44px
  left: 1206px
  top: 40px
  font-family: Roboto
  font-style: normal
  font-weight: normal
  font-size: 30px
  line-height: 30px
  /* or 100% */
  letter-spacing: 0.3em
  color: #9A8C98

.w5title
  position: absolute
  width: 376px
  height: 57px
  left: 159px
  top: 976px
  font-family: Roboto
  font-style: normal
  font-weight: normal
  font-size: 30px
  line-height: 30px
  /* or 100% */
  letter-spacing: 0.3em
  color: #9A8C98

.w6title
  position: absolute
  width: 347px
  height: 59px
  left: 701px
  top: 971px
  font-family: Roboto
  font-style: normal
  font-weight: normal
  font-size: 30px
  line-height: 30px
  /* or 100% */
  letter-spacing: 0.3em
  color: #9A8C98

.w7title
  position: absolute
  width: 192px
  height: 59px
  left: 1215px
  top: 971px
  font-family: Roboto
  font-style: normal
  font-weight: normal
  font-size: 30px
  line-height: 30px
  /* or 100% */
  letter-spacing: 0.3em
  color: #9A8C98

</style>
