<template>
    <header>
        <div class="container">
            <div class="logo">
                <img alt="Vue logo" src="@/assets/img/dc-logo.png">
            </div>

            <div class="nav_bar">
                <ul>
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
    </header>
</template>

<style lang="scss" scoped>
.container{
    display: flex;
    align-items: center;
    padding: 0.5rem 0;

    .logo{
        width: 30%;
    }

    .nav_bar{
        width: 70%;

        ul{
            list-style-type: none;
            text-decoration: none;

            li{
                display: inline-block;

                a{
                    text-decoration: none;
                    margin: 0 0.5rem;
                    color: black;
                }
            }       
        }
    }
}
</style>