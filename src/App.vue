<template>
  <div id="app">
   <BaseHeader/>
   <BaseMain/>
   <BaseFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/baseHeader.vue';
import baseMain from './components/baseMain.vue';
import baseFooter from './components/baseFooter.vue';

export default {
  name: 'App',
  components: {
    BaseHeader,
    baseMain,
    baseFooter,
  },
};
</script>

<style lang="scss">
@import './assets/style/global.scss';

</style>
