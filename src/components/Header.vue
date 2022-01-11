<template>
    <header>
        <div class="wrapper">
            <div class="logo">
                <img src="../assets/img/logo-dc.png" alt="Logo DC">
            </div>
            <nav>
                <ul class="menu">
                            <li>
                                <a href="#">Personaggi</a>
                            </li>
                            <li>
                                <a href="#">Comics</a>
                            </li>
                            <li>
                                <a href="#">Movie</a>
                            </li>
                            <li>
                                <a class="current" href="#">TV</a>
                            </li>
                            <li>
                                <a href="#">Games</a>
                            </li>
                            <li>
                                <a href="#">Collectables</a>
                            </li>
                            <li>
                                <a href="#">Videos</a>
                            </li>
                            <li>
                                <a href="#">Fans</a>
                            </li>
                            <li>
                                <a href="#">News</a>
                            </li>
                            <li>
                                <a href="#">Shop</a>
                            </li>

                </ul>
            </nav>
        </div>
    </header>
</template>

<script>

export default {
    name:'Header',
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";
header{
    

    .wrapper{
        height: 120px;
        display: flex;
        justify-content:space-between;
        align-items: center;
    

        /* Logo */
         .logo{
            img{
                width: 100px;
             }
        }

        /* menu */
        .menu{
            display: flex;
            li{
                margin-right: 50px;
                a{
                    display: inline-block;
                    color: black;
                    text-decoration: none;
                    font-size: 18px;
                    text-transform: uppercase;
                    font-weight: bold;
                    line-height: 115px;
                    &.current{
                        color: $colore-testi-secondario;
                        border-bottom: 5px solid $colore-testi-secondario;
                        
                    }
                }
            }
        }
    }
   
}
</style>