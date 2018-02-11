<!-- 我的测试 -->

<template>
  <div @click="haha">
    Test<br/>
    Test<br/>
    Test<br/>
    Test<br/>
    Test<br/>
    Test<br/>
    Test<br/>
  </div>
</template>
<script>
  export default {
    data () {
      return {}
    },
    props: {},
    watch: {},
    methods: {
      haha () {
        alert('Test')
      }
    },
    filters: {},
    computed: {},
    created () {
      this.haha()
    },
    mounted () {},
    destroyed () {}
  }
</script>
<style lang="scss" scoped>
  @import '~@/assets/scss/const.scss';
  @import '~@/assets/scss/mixin.scss';
</style>
