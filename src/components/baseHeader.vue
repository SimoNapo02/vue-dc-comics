<template>
  <header class="header">
        <div class="container">
            <div class="header__logo">
                <img src="../assets/img/dc-logo.png" alt="Dc logo">
            </div>
            <nav class="header__navbar">
                <ul class="header__list">
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
            </nav>
        </div>
  </header>
</template>

<script>
export default {
  name: 'BaseHeader',
};
</script>

<style lang="scss">
.header{

    & .container{
        height: 6.25rem;
    }
    & .container{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    &__navbar{
        ul{
            display: flex;
            list-style: none;
            gap: 1.25rem;
        }
        a{
            text-decoration: none;
            display: inline-block;
            color: var(--text-darkgrey);
            font-weight: bold;
            border: 4px solid transparent;
        }
        a:hover{
            color: var(--primary-color);
            border-bottom:solid 4px var(--primary-color);
            left: 25%;
            right: 25%;
            bottom: 0;
        }

    }
    &__logo img{
        width: 5rem;
    }
}
</style>
