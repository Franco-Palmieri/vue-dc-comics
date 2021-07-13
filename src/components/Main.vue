<template>
    <div class="main">
        <div class="container">
            <div class="content-comics">
                <Card v-for="(comic, index) in comics" :key="index" :comic="comic"/>
            </div>
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
        background-color: rgb(19, 19, 19);
        .content-comics{
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
        }
    }
</style>