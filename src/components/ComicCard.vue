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
        <img :src="thumbUrl" alt="{{ series }}">
        <figcaption> {{ series.toUpperCase() }} </figcaption>
    </figure>

</template>

<style lang="scss" scoped>
.comic-card {
    width: 100%;
    cursor: pointer;

    img {
        width: 200px;
        height: 200px;
        object-fit: contain;
    }

    figcaption {
        color: white;
        font-size: 14px;
        text-align: center
    }

    transition: all .2s ease-in-out;

    &:hover {
        transform: scale(1.2);
    }
}
</style>