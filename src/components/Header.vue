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
        align-items: center;
        height: 110px;
        justify-content: space-between;
        margin-top: 20px;
        
        .logo{
            width: 150px;
            .img{
                width: 100% ;
                vertical-align: middle;
            }
        }
        .top-list{
            display: flex;
            height: 110px;
            li{
                line-height: 110px;
                list-style: none;
                margin: 0 10px;
                &:hover{
                    border-bottom: 2px solid rgb(62, 146, 255);
                }
                
                a{
                    text-decoration: none;
                    color: rgb(61, 61, 61);
                    font-weight: bold;
                    &:hover{
                    color: rgb(62, 146, 255);
                    }
                }
            }
        }
}
</style>