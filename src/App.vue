<script>
  import AppHeader from './components/AppHeader.vue';
  import AppMain from './components/AppMain.vue';
  import AppFooter from './components/AppFooter.vue';

export default{
    name: "App",

    data() {
        return {
          
        };
    },

    components: {
      AppHeader,
      AppMain,
      AppFooter,
    }
}
</script>

<template>
  <AppHeader/>
  <AppMain/>
  <AppFooter/>

</template>

<style lang="scss">
  @import "bootstrap/scss/bootstrap";
  @import './styles/general.scss';

</style>
