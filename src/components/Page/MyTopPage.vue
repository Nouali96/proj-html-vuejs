<template>
    <div class="fixed text-center">     
        <a href="#"><div><i class="fa-solid fa-angle-up fa-2x angle-up"></i><span>TOP</span></div></a>     
    </div>
</template>

<script>
export default {
    name:'MyTopPage',
}
</script>

<style  lang="scss">
    .fixed {
        position: fixed;
        bottom: 0;
        right: 0;
        width: 70px;
        height: 70px;
        background-color: #3FC4FF;
        display: block;    
    }
    .fixed a{
       font-size: 15px;
       margin: auto;
       height: 20px!important;
       color: white;
    }
    .fixed span{
        position: fixed;
        bottom: 0;
        right: 0;
        margin: 5px 15px 12px 0;
    }
</style>