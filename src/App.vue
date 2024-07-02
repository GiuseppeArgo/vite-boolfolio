<script>
import AppMain from './components/AppMain.vue';
import { router } from './router';

export default {
  components: {
    AppMain,
  },
}
</script>

<template>
  <router-view></router-view>
  <AppMain />

</template>

<style scoped lang="scss">

</style>
