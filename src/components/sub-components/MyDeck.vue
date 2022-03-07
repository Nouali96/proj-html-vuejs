<template>
    <div class="container pb-5">
        <div class="row text-center d-flex justify-content-around py-3">
            <MyCard img="./assets/img/h5-custom-icon-1.png" titlec="Languages"/>
            <MyCard img="./assets/img/h5-custom-icon-2.png" titlec="Software"/>
            <MyCard img="./assets/img/h5-custom-icon-3.png" titlec="Business"/>
            <MyCard img="./assets/img/h5-custom-icon-4.png" titlec="Chemistry"/>
            <MyCard img="./assets/img/h5-custom-icon-5.png" titlec="Science"/>
            <MyCard img="./assets/img/h5-custom-icon-6.png" titlec="DIY&Craft"/>
        </div>
    </div>
</template>

<script>
import MyCard from './MyCard.vue' 
export default { 
    name: 'MyDeck',
    components:{
        MyCard,
    }
}
</script>

<style lang="scss">

</style>