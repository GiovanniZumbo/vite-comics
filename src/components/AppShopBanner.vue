<script>
export default {
  data() {
    return {

    }
  }
}
</script>

<template>
  <main>
    <div class="container">
      <div class="buying-section">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <a href="#">DIGITAL COMICS</a>
      </div>

      <div class="buying-section">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <a href="#">DC MERCHANDISE</a>
      </div>

      <div class="buying-section">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <a href="#">SUBSCRIPTION</a>
      </div>
      <div class="buying-section">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <a href="#">COMIC SHOP LOCATOR</a>
      </div>
      <div class="buying-section">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        <a href="#">DC POWER VISA</a>
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