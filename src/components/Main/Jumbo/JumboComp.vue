<template>
  <div>
    <h4>Jumbo Section</h4>
    <JumboTop/>
    <JumboMid/>
    <JumboBottom/>
  </div>
</template>

<script>
import JumboTop from './JumboTop.vue'
import JumboMid from './JumboMid.vue'
import JumboBottom from './JumboBottom.vue'

export default {
  name: 'JumboComp',
  components: {
      JumboTop,
      JumboMid,
      JumboBottom
  }
}
</script>

<style scoped lang="scss">

</style>