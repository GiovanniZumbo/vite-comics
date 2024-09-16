<script>
// Imported components
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

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
  AppFooter
}

}

</script>

<template>
<body>
  <div>

      <AppHeader/>
      <AppMain/>
      <AppFooter/>

</div>
  
</body>
</template>

<style lang="scss">
@use "./styles/generics.scss" as *;

</style>