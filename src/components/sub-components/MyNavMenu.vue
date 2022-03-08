<template>
 <div>
    <li class="nav-item">
        <div class="nav-link" v-if="searchClicked"><input type="text" placeholder="Cerca..."><i @click="xclicked()" class="fa-solid fa-xmark" style="margin-left: 10px; color:white; cursor: pointer;"></i></div>
        <a class="nav-link" v-else :href="menu.link" @click="clicked(menu)" :id="menu.type">
            <i v-if="menu.type == 'search'" class="fa-solid fa-magnifying-glass"></i>
            <i v-if="menu.type == 'market'" class="fa-regular fa-clipboard"></i>
            <i v-if="menu.type == 'menu'" class="fa-solid fa-bars"></i>
            {{menu.name}}
        </a> </li>
 </div>
</template>

<script>
export default {
    name: 'MyNavMenu',
    props: {
        menu: Object
    },
    data(){
        return {
            searchClicked: false,
        }
    },
    methods:{
        clicked: function(menu){
            if(menu.type=='search'){
                this.searchClicked=true
            }
            else{
                menu.fn()
            }
        },
        xclicked: function(){
            this.searchClicked=false
        } 
    }
}
</script>

<style>
</style>