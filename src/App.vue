<script>
// Imported components
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppShopBanner from './components/AppShopBanner.vue';

// // imported font
// import "@fontsource/oswald";
// import "@fontsource/oswald/400.css";
// import "@fontsource/oswald/400-italic.css";


export default {
  data() {
    return {

    }
  },

components: {
  AppHeader,
  AppMain,
  AppFooter,
  AppShopBanner
}

}

</script>

<template>
<body>
  <div>

      <AppHeader/>
      <AppMain/>
      <AppShopBanner/>
      <AppFooter/>

</div>
  
</body>
</template>

<style lang="scss">
@use "./styles/generics.scss" as *;

</style>