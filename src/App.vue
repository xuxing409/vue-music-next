<template>
  <m-header></m-header>
  <tab></tab>
  <router-view></router-view>
</template>

<script>
import Header from '@/components/header/header'
import Tab from '@/components/tab/tab'
export default {
  name: 'app',
  components: {
    MHeader: Header,
    Tab
  }
}
</script>

<style lang="scss">

</style>
