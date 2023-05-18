<script>
    export default {
        
    }
</script>

<template>
    <div class="background">
        <div class="container-header">
            <div class="digital-comics">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="dc-merchandise">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISES</span>
            </div>
            <div class="dc-subscription">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="comic-shop-locator">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="dc-power-visa">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
    <div class="background-img">
        <div class="container-body">
            <div>
                <ul class="dc-comics">
                <li>
                    <h2>DC COMICS</h2>
                </li>
                <li class="little moar opacity-50">Characters</li>
                <li class="little opacity-50">Comics</li>
                <li class="little opacity-50">Movies</li>
                <li class="little opacity-50">TV</li>
                <li class="little opacity-50">Games</li>
                <li class="little opacity-50">Videos</li>
                <li class="little opacity-50">News</li>
            </ul>
            <ul class="shop">
                <li class="moar">
                    <h2>SHOP</h2>
                </li>
                <li class="little moar opacity-50">Shop DC</li>
                <li class="little opacity-50">Shop DC Collectibles</li>
            </ul>
            </div>
            <div>
                <ul class="dc">
                    <li>
                        <h2>DC</h2>
                    </li>
                    <li class="little moar opacity-50">Terms Of Use</li>
                    <li class="little opacity-50">Privacy policy (New)</li>
                    <li class="little opacity-50">Ad choices</li>
                    <li class="little opacity-50">Advertising</li>
                    <li class="little opacity-50">Jobs</li>
                    <li class="little opacity-50">Subscriptions</li>
                    <li class="little opacity-50">Talent Workshops</li>
                    <li class="little opacity-50">CPSC Certificates</li>
                    <li class="little opacity-50">Ratings</li>
                    <li class="little opacity-50">Shop Help</li>
                    <li class="little opacity-50">Contact Us</li>
                </ul>
            </div>

            <div>
                <ul class="sites">
                    <li>
                        <h2>SITES</h2>
                    </li>
                    <li class="little moar opacity-50">DC</li>
                    <li class="little opacity-50">MAD Magazine</li>
                    <li class="little opacity-50">DC Kids</li>
                    <li class="little opacity-50">DC Universe</li>
                    <li class="little opacity-50">DC Power Visa</li>
                </ul>
            </div>

            <div class="background-dc">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
    <div class="background-gray">
        <div class="container-footer">
            <button>SIGN-UP NOW!</button>
            <div class="follow-us">
                <span>FOLLOW US</span>
                <img src="./../assets/img/footer-facebook.png" alt="">
                <img src="./../assets/img/footer-twitter.png" alt="">
                <img src="./../assets/img/footer-youtube.png" alt="">
                <img src="./../assets/img/footer-pinterest.png" alt="">
                <img src="./../assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
         
</template>



<style lang="scss" scoped>
    @use './../assets/styles/partials/variables.scss' as *;
    $white-color: white;
    .background{
        background-color: #0282F9;
    }

    .container-header{
        @include width-1100;
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: $white-color;
        z-index: 1000;
        div{
            display: flex;
            align-items: center;
            gap: 0.5rem;
            span{
                font-size: 1rem;
            }
        }
        img{
            max-width: 50px;
        }
    }

    .background-img{
        background-image: url(../assets/img/footer-bg.jpg);
        height: 370px;
        color: white
    }

    .container-body{
        @include width-1100;
        display: flex;
        gap: 4rem;
        position: relative;
        z-index: 1000;
    }

    ul{
        list-style-type: none;
            li{
            margin-top: 0.4rem;
            }
    }
    .little{
        font-size: 0.8rem;
    }

    .moar{
        margin-top: 1rem;
    }
    .opacity-50{
        opacity: 50%;
    }
    .background-dc{
        width: 785px;
        height: 370px;
        overflow: hidden;
       
        img{
            width: auto;
            position: relative;
            top: -120px;
            right: -73px;
        }
    }
    .background-gray{
        background-color: #303030;
        height: 109px;
        color: white;
        .container-footer{
            @include width-1100-noheight;
            height: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            button{
                background-color: #303030;
                border: 2px solid #0282F9;
                color: white;
                padding-inline: 1.5rem;
                padding-top: 0.75rem;
                padding-bottom: 0.75rem;
                font-size: 1.2rem;
            }
            .follow-us{
                display: flex;
                align-items: center;
                justify-content: space-between;
                gap: 1rem;
                color: #0271C1;
            }
        }
    }


    
  


</style>