<script>

    export default {
        props: {
            urlImg: String,
            titolo: String,
        }
    }
</script>


<template>
    <div class="card">
            <div class="magazine-pic">
                <img :src=" /*arrMagazines[0].thumb*/ urlImg " alt="">
            </div>
            <div class="magazine-series"> {{ /*arrMagazines[0].series.toUpperCase()*/ titolo.toUpperCase() }} </div>
    </div>
</template>



<style lang="scss" scoped>
    .card{
        width: 150px;
        height: 200px;
        display: flex;
        gap: 0.2rem;
        font-size: 1rem;
        display: flex;
        flex-direction: column;
        img{
            width: 150px;
            height: 200px;
            object-fit: cover;
        }
        .magazine-series{
            text-align: center;
        }
    }
    
            
        
</style>