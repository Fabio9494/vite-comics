<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import CardFumetti from './components/CardFumetti.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    CardFumetti
  }
}
</script>

<template lang="">
    <AppHeader/>
    <AppMain/>
    <AppFooter/>
    <CardFumetti/>
</template>

<style lang="scss" scoped></style>