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
    <div class="underline"></div>
    
</div>
</template>



<style lang="scss" scoped>
    .submenu{
        position: relative;
            &:hover{ 
            cursor: pointer;
            color: #0282F9;
            
            }
            &:hover .underline{
                display: block;
            }

            &::after{
            background-color: #0282F9;
            height: 2px;
            width: 100%;
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            }  
        }
        .underline{
            background-color: #0282F9;
            height: 5px;
            width: 106%;
            position: absolute;
            top: 3.9rem;
            left: -3px;
            right: 0;
            display: none;
            
            
        }
</style>