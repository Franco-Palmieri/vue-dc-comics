<template>
    <div class="header container">
        <div class="nav">
            <div class="logo">
                <img src="../assets/dc-logo.png">
            </div>
            <ul class="top-list">
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
    .nav{
        display: flex;
        justify-content: space-around;
        align-items: center;
        .logo{
            border: 1px solid black;
            width: 400px;
            .img{
                width: 100% ;
            }
        }
        .top-list{
            display: flex;
            flex-grow: 1;
            li{
                padding: 10px;
                list-style: none;
                margin: 0 5px;
                border: 1px solid blue;
                a{
                    text-decoration: none;
                    color: black;
                }
            }
        }

    }
</style>