<script>
    import AppNav from './AppNav.vue';
    export default {
        components: {
            AppNav,
        },

        data() {
            return {
                arrNav: [
                    {
                        'object': "CHARACTERS",
                    },
                    {
                        'object': "COMICS",
                    },
                    {
                        'object': "MOVIES",
                    },
                    {
                        'object': "TV",
                    },
                    {
                        'object': "GAMES",
                    },
                    {
                        'object': "COLLECTIBLES",
                    },
                    {
                        'object': "VIDEOS",
                    },
                    {
                        'object': "FANS",
                    },
                    {
                        'object': "NEWS",
                    },
                    {
                        'object': "SHOP",
                    },
                ]
            }
        }
    }
</script>

<template>
    <header>
        <div>
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="nav-bar">
            <AppNav
                v-for="(nav, i) in arrNav"
                :key="i"
                :navObject="nav.object"
            />
            
        </div>
    </header>
</template>



<style lang="scss" scoped>
    @use './../assets/styles/partials/variables.scss' as *;
    header{
        @include width-1100-noheight;
        height: 120px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        img{
            width: 80%;
        }
    }

    .nav-bar{
        display: flex;
        align-items: center;
        gap: 1.2rem;
        font-size: 0.8rem;
        font-weight: 900;
        
       
    }

       



</style>    