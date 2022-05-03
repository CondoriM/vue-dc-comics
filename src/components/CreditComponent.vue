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

        </div>
    </div>
</template>

<style lang="scss" scoped>

.container{
    background-image: url('@/assets/img/footer-bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
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

</style>