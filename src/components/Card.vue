<template>
    <div class="comic-cart">
        <div class="image-comic">
            <img :src="comic.thumb" alt="">
            <div class="comic-name">{{comic.series}}</div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Card",
    props: ["comic"],
}
</script>

<style scoped lang="scss">
    .comic-cart{
        width: calc(100% / 6);
        padding: 0 15px;
        height: 250px;
        .comic-name{
            color: white;
            font-size: 15px;
        }
        img{
            width: 100%;
            height: 200px;
        }
    }

</style>