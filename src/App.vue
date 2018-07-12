<template>
  <div id="app">
    <x-header >
    <router-view></router-view>
  </div>
</template>

<script>
import XHeader from "vux/src/components/x-header/index";

export default {
  components: {XHeader},
  name: 'app'
}
</script>

<style lang="less">
@import '~vux/src/styles/reset.less';

body {
  background-color: #fbf9fe;
}
</style>
