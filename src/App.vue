<template>
  <div id="app">
    <MyHeader/>
    <MyMain/>
    <MyFooter/>
    <MyTopPage/> 
  </div>
</template>

<script>
import MyHeader from './components/Page/MyHeader.vue'
import MyMain from './components/Page/MyMain.vue'
import MyFooter from './components/Page/MyFooter.vue'
import MyTopPage from './components/Page/MyTopPage.vue'


export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter,
    MyTopPage
  }
}
</script>

<style lang="scss">
@import "./assets/style/general.scss";
</style>
