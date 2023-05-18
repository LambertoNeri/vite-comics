<script>
    export default {
        
    }
</script>

<template>
    <div class="background">
        <div class="container">
            <h1>--&gt; Content goes here &lt;-- </h1>
        </div>
    </div>
   
</template>



<style lang="scss" scoped>
@use './../assets/styles/partials/variables.scss' as *;  
    .background{
        background-color: black;
    }
    .container{
        @include width-1100;
        color: white;
        display: flex;
        align-items: center;
    }
</style>

<style lang="scss">
.background{
    position: relative;
    z-index: 1000;
}
        
</style>