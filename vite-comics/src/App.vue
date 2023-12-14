<script>
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue';
import BigFooter from './components/BigFooter.vue';
import SmallFooter from './components/SmallFooter.vue'

export default {
  name: 'App',
  components:{
    AppHeader,
    AppContent,
    BigFooter,
  SmallFooter}
}
</script>

<template>
  <AppHeader/>
  <AppContent/>
  <BigFooter/>
  <SmallFooter/>
  
</template>

<style scoped>


</style>
