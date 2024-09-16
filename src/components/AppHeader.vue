<script>
export default {
  data() {
    return {
      navLinks:[
        "characters","comics","movies","tv","games","collectibles","videos", "fans", "news", "shop"
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
            <li>characters</li>
            <li>comics</li>
            <li>movies</li>
            <li>tv</li>
            <li>games</li>
            <li>collectibles</li>
            <li>videos</li>
            <li>news</li>
            <li>shop</li>
        </ul>
    </nav>
</div>
</main>
</template>

<style lang="scss" scoped>
 
 main{
    background-color: white;
    height: 120px;
 }

 .container{
    height: 100%;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
 }
 
 ul{
    display: flex;
    list-style-type: none;
    gap: 10px;

    li{
        text-transform: uppercase;
        font-weight: bold;
    }
 }

</style>