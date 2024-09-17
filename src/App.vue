<script>
// Imported components
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppShopBanner from './components/AppShopBanner.vue';
import JumboBanner from './components/JumboBanner.vue';



export default {
  data() {
    return {

    }
  },

  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppShopBanner,
    JumboBanner

  }

}

</script>

<template>

  <body>
    <div>

      <AppHeader />
      <JumboBanner />
      <AppMain />
      <AppShopBanner />
      <AppFooter />
      <ComicCard />

    </div>

  </body>
</template>

<style lang="scss">
@use "./styles/generics.scss" as *;

// G-Fonts
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap');
</style>