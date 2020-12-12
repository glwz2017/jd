<template>
  <div class="home">
    {{ data }}
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      data: '我是首页999'
    }
  },
  created () { },
  mounted () { }
}
</script>
<style lang="less" scoped>
@import "../css/element.less";
@colorPink: pink;

.home {
  color: @colorPink;
  font-size: 96px;
}
</style>
