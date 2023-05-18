<script>
    export default {
        
    }
</script>

<template>
    <header>
        <div>
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="nav-bar">
            <div class="characters">CHARACTERS</div>
            <div class="comics">COMICS</div>
            <div class="movies">MOVIES</div>
            <div class="tv">TV</div>
            <div class="games">GAMES</div>
            <div class="collectibles">COLLECTIBLES</div>
            <div class="videos">VIDEOS</div>
            <div class="fans">FANS</div>
            <div class="news">NEWS</div>
            <div class="shop">SHOP</div>
        </div>
    </header>
</template>



<style lang="scss" scoped>
    @use './../assets/styles/partials/variables.scss' as *;
    header{
        @include width-1100;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .nav-bar{
        display: flex;
        align-items: center;
        gap: 1rem;
    }

</style>    