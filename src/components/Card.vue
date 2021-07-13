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
    props: ["comics"],
}
</script>

<style scoped lang="scss">

</style>