<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <div class="box">
                    <div class="img_card">
                        <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
                    </div>
                    <span>DIGITAL COMICS</span>
                </div>
            </div>

            <div class="col">
                <div class="box">
                    <div class="img_card">
                        <img src="@/assets/img/buy-comics-merchandise.png" alt="">
                    </div>
                    <span>DC MERCHANDISE</span>
                </div>
            </div>

            <div class="col">
                <div class="box">
                    <div class="img_card">
                        <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
                    </div>
                    <span>SUBSCRIPTION</span>
                </div>
            </div>

            <div class="col">
                <div class="box">
                    <div class="img_card">
                        <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
                    </div>
                    <span>COMIC SHOP LOCATOR</span>
                </div>
            </div>

            <div class="col">
                <div class="box">
                    <div>
                        <img id="svg" src="@/assets/img/buy-dc-power-visa.svg" alt="">
                    </div>
                    <span>DC POWER VISA</span>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>

    .container{
        background-color: var(--bg-foot);
        padding: 2rem 0;
        color: white;

        .box{

            display: flex;
            justify-content: center;
            align-items: center;
            text-align: left;
            
            .img_card{
                width: 20%;

                img{
                    width: 100%;
                }
            }

            span{
                width: 80%;
            }
        }

        #svg{
            width: 40%;
        }
    }

</style>