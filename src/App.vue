<template>
  <div id="app">
    <div id="nav">
      <MainNav/>
    </div>
    <router-view/>
  </div>
</template>

<style>

</style>

<script>
import MainNav from '@/components/MainNav'
export default {
  components: {
    MainNav
  }
}
</script>
