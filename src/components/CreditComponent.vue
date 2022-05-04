<template>
    <div class="container">
        <div class="credits">
            <div class="box_list">
                <div class="first_box">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>

                    <h3>SHOP</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                    </ul>
                </div>

                <div class="second_box">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                    </ul>
                </div>

                <div class="third_box">
                    <h3>DC</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                    </ul>
                </div>

            </div>

            <div class="logo_bg">
                <img src="@/assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>

        <div class="socials">
            <div class="sing-up">
                <a href="#">SING-UP NOW!</a>
            </div>

            <div class="follow">
                <span>FOLLOW US</span>
                
                <img src="@/assets/img/footer-facebook.png" alt="">
                <img src="@/assets/img/footer-twitter.png" alt="">
                <img src="@/assets/img/footer-youtube.png" alt="">
                <img src="@/assets/img/footer-pinterest.png" alt="">
                <img src="@/assets/img/footer-periscope.png" alt="">
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "SiteCredit",
}
</script>

<style lang="scss" scoped>

.container{
    background-image: url('@/assets/img/footer-bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    position: relative;
}

.credits{
    display: flex;
    padding: 2rem 0;
    width: 80%;
    margin: auto;
    justify-content: space-between;

    .box_list{
        display: flex;
        color: white;
        gap: 3rem;
        text-align: left;

        ul{
            list-style-type: none;
            text-align: left;
            
            a{
                text-decoration: none;
                color: var(--text-foot);
            }
        }
    }

    .logo_bg{
        position: relative;

        img{
            margin: -130px 0 0 0;
        }
    }
}

.socials{
    display: flex;
    background-color:var(--bg-foot-second) ;
    width: 100%;
    position: absolute;
    bottom: 0;
    padding: 1.5rem;

    .sing-up{
        width: 50%;

        a{
            text-decoration: none;
            color: white;
            padding: 0.5rem;
            border: 2px solid;
            border-color: var(--bg-foot);
        }
    }

    .follow{
        width: 50%;
        display: flex;
        gap: 0.5rem;
        align-items: center;
        justify-content: center;

        span{
            color: var(--bg-foot);
        }
    }
}

</style>