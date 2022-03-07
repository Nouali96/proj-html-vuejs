<template>
    <div class="xcard col-5 mt-5">
        <a href="#">
            <div class="col-12 py-5 ">
                <img :src="img" alt="">
            </div>
            
            <div class="col-12 py-1">
                <span>{{titlec}}</span>
            </div>
        </a>
    </div>
</template>

<script>

export default {
    name: 'MyCard',
    props: {
            "img": String,
            "titlec": String
        }
}
</script>

<style  lang="scss">
.xcard{
    background-color: #F2F8FC;
    height: 250px;
    width: 200px;
    padding: 0;
}
.xcard a{
    color: black;
    font-weight: bold;
    display: block;
    height: 100%;
    width: 100%;
    text-decoration: none;
    margin-left: 0;
}
.xcard:hover{
    border-bottom: 5px solid #40C4FF;
}
</style>