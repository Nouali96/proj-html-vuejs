<template>
 <div>
    <li class="nav-item">
        <a class="nav-link" :href="menu.link" @click="menu.fn">
            <i v-if="menu.type == 'search'" class="fa-solid fa-magnifying-glass"></i>
            <i v-if="menu.type == 'market'" class="fa-regular fa-clipboard"></i>
            <i v-if="menu.type == 'menu'" class="fa-solid fa-bars"></i>
            {{menu.name}}</a>
    </li>
 </div>
</template>

<script>
export default {
    name: 'MyNavMenu',
    props: {
        menu: Object
    }
}
</script>

<style>

</style>