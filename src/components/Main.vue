<template>
    <div class="main">
        <div class="container">
            <Card v-for="(comic, index) in comics" :key="index" :comic="comic"/>
        </div>
    </div>
</template>

<script>
import Card from "./Card.vue"

export default {
    name: 'Main',
    components:{
        Card,
    },
    props: ["comics"],
}
</script>

<style scoped lang="scss">
    .main{
        height: 100px;
        background-color: #ccc;
    }
</style>