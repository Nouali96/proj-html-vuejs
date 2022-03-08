<template>
    <div>
    <div class="container-header">
        <div class="dark">
            <nav class="pt-5">
                <ul class="nav d-flex justify-content-center">
                    <img class="px-5 mx-5" src="..\public\assets\img\logo-light.png" alt="">
                    <MyNavMenu v-for="(item, index) in list" :key="index" :menu="item"/>
                </ul>
            </nav>
            <div class="text-center pt-5 ">
                <div class="box-header">
                    <h1 class="pt-5 mt-5 fs-h1-header">Contemporary Ideas</h1>
                    <div class="mt-4"><span>Lorem, ipsum dolor sit amet consectetur adipisicing elit. In nihil quidem voluptate iusto totam velit iure libero voluptatem ipsa est illum repellendus, cupiditate rerum? At praesentium odio laborum consequuntur saepe!</span></div>
                    <div class="mt-5"><button class="button-1"><span>REGISTER NOW</span></button></div>
                </div>
            </div>
        </div>
    </div>
    <MyDeck/>
    </div>
</template>

<script>
import MyDeck from '../sub-components/MyDeck.vue'
import MyNavMenu from '../sub-components/MyNavMenu.vue'
export default {
    name: 'MyHeader',
    components: {
        MyDeck,
        MyNavMenu,
    },
    data () {
    return {
      list: [{
          name:'HOME',
          link:'#',
          type:'',
          fn:function (){},
      },
      {
          name:'COURSES',
          link:'#',
          type:'',
          fn:function (){},
      },
      {
          name:'INSTRUCTORS',
          link:'#',
          type:'',
          fn:function (){},
      },
      {
          name:'EVENTS',
          link:'#',
          type:'',
          fn:function (){},
      },
      {
          name:'PAGES',
          link:'#',
          type:'',
          fn:function (){},
      },
      {
          name:'ELEMENTS',
          link:'#',
          type:'',
          fn:function (){},
      },
      {
          name:'',
          link:'#',
          type:'search',
          fn:function (){},
      },
      {
          name:'',
          link:'#',
          type:'market',
          fn:function (){},
      },
      {
          name:'',
          link:'#',
          type:'menu',
          fn:function (){},
      },
      ]
    }
  }
    
}
</script>

<style lang="scss">
@import "@/assets/style/general.scss";
.container-header{
    height: 900px;
    background-image: url("/public/assets/img/course-9-f-img.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    color: #FDFDFD;
}
.nav img{
    height: 40px;
}
.nav a {
    color: #FDFDFD;
}
.dark{   
    background-color: rgba(0, 0, 0, 0.25);
    height: 100%;
}

.fs-h1-header{
    font-size: 80px;
    font-weight: bold;
}
.box-header{
    width: 900px;
    margin: auto;
}
</style>