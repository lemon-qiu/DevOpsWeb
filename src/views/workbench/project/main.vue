<template>
  <div id="project-app">
    aaa
    cc
  </div>
</template>

<script type="text/ecmascript-6">
  import {title} from 'config/config';
  export default {
    created () {
      document.title = title;
    },
    data () {
      return {};
    },
    methods: {}
  };
</script>

<style lang="scss" rel="stylesheet/scss" scoped>
  #project-app{
    height: 100%;
    width: 100%;
  }
</style>
