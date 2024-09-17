<script>
export default {
    data() {
        return {

        }
    },

    props: {
        thumbUrl: {
            type: String,
            required: true,
        },

        series: {
            type: String,
            required: true,
        }
    }
}

</script>

<template>

    <figure class="comic-card">
        <img :src="thumbUrl" alt="">
        <figcaption> {{ series }} </figcaption>
    </figure>

</template>

<style lang="scss" scoped>
.comic-card {
    width: 200px;
    aspect-ratio: 1;


    img {
        max-width: 100%;
    }

    figcaption {
        color: white;
    }


}
</style>