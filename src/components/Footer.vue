<template>
    <div class="footer">
        <div class="blue-bar">
            <ul class="container">
                <li><img src="../assets/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</li>
                <li><img src="../assets/buy-comics-merchandise.png" alt="">DC MERCHANDISE</li>
                <li><img src="../assets/buy-comics-subscriptions.png" alt="">SUBSCRIPTION</li>
                <li><img src="../assets/buy-comics-shop-locator.png" alt="">COMICS SHOP LOCATER</li>
                <li><img src="../assets/buy-dc-power-visa.svg" alt="">DC POWER VISA</li>
            </ul>
        </div>
        <div class="bg-footer">
            <div class="container foot-list">
                <ul>
                    <li>DC COMICS</li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <ul>
                    <li>DC</li>
                    <li><a href="#">Tems of Use</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshop</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
                <ul>
                    <li>SITES</li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
                <ul>
                    <li>SHOP</li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </div>
            <div class="pic-foot">
                <img src="../assets/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="bottom-footer">
            <div class="container content-bottom-foot">
                <div class="button-foot">
                    <button>SIGN-UP NOW!</button>
                </div>
                <div class="social-list">
                    <ul>
                        <li>FOLLOW US</li>
                        <li><a href="#"><img src="../assets/footer-facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-twitter.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-youtube.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-pinterest.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-periscope.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
    .footer{
       
        .blue-bar{
            height: 150px;
            background-color: rgb(62, 146, 255);
            ul{
                display: flex;
                align-items: center;
                color: white;
                justify-content: space-around;
                line-height: 150px;
                li{
                    align-items: center;
                    display: flex;
                    img{
                        width:40px;
                        margin: 0 5px
                    }
                }
            }
        }
        .bg-footer{
            background-image: url("../assets/footer-bg.jpg");
            display:flex;
            padding: 20px;
            height: 400px;
            .foot-list{
                display: flex;
                flex-wrap: wrap;
                ul{
                    color: white;
                    list-style: none;
                    margin: 0 15px;
                    flex-basis: calc(100% / 4);
                    li{
                        font-size: 12px;
                        margin: 5px 0;
                        &:first-child{
                        font-weight: bold;
                        margin: 10px 0;
                        }
                        
                        a{
                            text-decoration: none;
                            color: rgba(255, 255, 255, 0.5);
                            
                            &:hover{
                            color: white;
                            }
                        }
                    }
                }
            }
        }
        .pic-foot{
            widows: 50%;
            text-align: center;
            img{
                width:60%;
            }
        }
        .bottom-footer{
            padding: 20px;
            background-color: rgb(65, 65, 65);
            .button-foot{
                button{
                    padding: 10px;
                    background-color: rgb(65, 65, 65);
                    border: rgb(62, 146, 255) 1px solid;
                    color: white;
                }
            }
            .content-bottom-foot{
                display: flex;
                align-items: center;
                justify-content: space-between;
                .social-list{
                    ul{
                        display: flex;
                        align-items: center;
                        li{
                            margin: 0 10px;
                            list-style: none;
                            &:first-child{
                                color: rgb(62, 146, 255);
                                font-weight: bold;
                            }
                            a{
                                img{
                                    width: 100%;
                                }
                            }
                        }
                    }
                }
            }
        }
    }
</style>