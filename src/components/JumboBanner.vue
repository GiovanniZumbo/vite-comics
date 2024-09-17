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
        <div class="jumbo-content">
            <div class="jumbo-text">
                <h2>TEEN TITANS:</h2> <span>Watch the new episodes on DC-TV!</span>
            </div>

        </div>

    </main>

</template>

<style lang="scss" scoped>
main {


    // css

    height: 500px;
    background-image: url(../assets/img/jumbotron.jpg);
    background-size: cover;
    background-repeat: no-repeat;

    position: relative;


    .jumbo-content {
        width: 100%;
        height: 100%;
        background-color: rgba($color: #000000, $alpha: 0.4);
        padding: 30px;

        position: relative;

        .jumbo-text {
            font-size: 30px;
            color: gold;

            position: absolute;
            right: 30px;
            bottom: 50px;
        }
    }

}
</style>