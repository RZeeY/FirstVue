<template>
  <div id="app">
    <HeaderV></HeaderV>
    <AboutV></AboutV>
    <DrawV></DrawV>
    <CommentV></CommentV>
    <AwardV></AwardV>
    <RulesV></RulesV>
  </div>
</template>

<script>
import HeaderV from './components/Header.vue'
import AboutV from './components/About.vue'
import DrawV from './components/Draw.vue'
import CommentV from './components/Comment.vue'
import AwardV from './components/Award.vue'
import RulesV from './components/Rules.vue'

export default {
  name: 'app',
  components: {
    HeaderV,
    AboutV,
    DrawV,
    CommentV,
    AwardV,
    RulesV
  },
  data () {
    return {

    }
  }
}
</script>

<style>
@import '../src/assets/css/reset.css'
</style>
