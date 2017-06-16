<template>
  <div id="app">
    <Keep-Header></Keep-Header>
    <router-view></router-view>
  </div>
</template>

<script>
  import KeepHeader from '@/components/Header'

  export default {
    components: {
      KeepHeader
    }
  }
</script>

<style lang="scss">
  @import 'style/base'
</style>
