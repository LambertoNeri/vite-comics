<script>
  
    export default {
        props: {
            navObject: String,
        }
    }
</script>


<template>
<div class="submenu">
    {{ navObject }}
</div>
</template>



<style lang="scss" scoped>
    div{
        position: relative;
            &:hover{ 
            cursor: pointer;
            color: #0282F9;
            }

            &:after{
            background-color: #0282F9;
            height: 2px;
            width: 100%;
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            }  
        }
</style>