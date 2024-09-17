<script>
export default {
  data() {
    return {
      shopItemList: [
        {
          name: "DIGITAL COMICS",
          icon: "../assets/img/buy-comics-digital-comics.png"
        },
        {
          name: "DC MERCHANDISE",
          icon: "../assets/img/buy-comics-merchandise.png"
        },
        {
          name: "SUBSCRIPTION",
          icon: "../assets/img/buy-comics-subscriptions.png"
        },
        {
          name: "COMIC SHOP LOCATOR",
          icon: "../assets/img/buy-comics-shop-locator.png"
        },
        {
          name: "DC POWER VISA",
          icon: "../assets/img/buy-dc-power-visa.svg"
        }
      ]
    }
  },
  methods: {
    getImagePath: function (imgPath) {
      return new URL(imgPath, import.meta.url).href;
    }
  }
}
</script>

<template>
  <main>
    <div class="container">

      <div class="buying-section" v-for="shopItem in shopItemList">
        <img :src="getImagePath(shopItem.icon)" alt="">
        <a href="#">{{ shopItem.name }}</a>
      </div>

    </div>
  </main>
</template>

<style lang="scss" scoped>
main {
  background-color: var(--electric-blue);
}

.container {
  color: white;
  display: flex;

  .buying-section {
    padding: 40px 20px;
    display: flex;
    align-items: center;
    flex-basis: 20%;

    img {
      width: 25%;
      aspect-ratio: 1;
      object-fit: contain;
    }

    a {
      color: white;
      font-size: 12px;
    }
  }
}
</style>