<script>
export default {
  data() {
    return {
      navLinks: [
        "characters", "comics", "movies", "tv", "games", "collectibles", "videos", "fans", "news", "shop"
      ]
    }
  }
}
</script>

<template>
  <main>
    <div class="container">
      <img src="../assets/img/dc-logo.png" alt="dc-logo">

      <nav>
        <ul>
          <li v-for="link in navLinks">{{ link }}</li>

        </ul>
      </nav>
    </div>
  </main>
</template>

<style lang="scss" scoped>
main {
  background-color: white;
  height: 130px;
}

.container {
  height: 100%;
  padding: 15px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

ul {
  display: flex;
  gap: 10px;

  li {
    text-transform: uppercase;
    font-size: 14px;
    letter-spacing: -1px;
    font-weight: bold;
    padding: 54px 0;
    border-bottom: 5px solid transparent;
  }


  li:hover {
    border-bottom: 5px solid var(--electric-blue);
    color: var(--electric-blue);
    cursor: pointer;
  }
}
</style>