<template>
    <div class="avatar">
       <div class="avatar_face">
           <img src="../assets/face.jpeg">
       </div>
           <p class="avatar_greet">hello 鹏宇</p>
           <h1 class="avatar_title">今天的预习课程有</h1>
           <search/>
    </div>
</template>

<script>
import Search from '../components/Search.vue'
export default {
     components:{
        "search":Search,
    },
}
</script>

<style>
.avatar{
    padding: 20px;
    height: 220px;
   
}
.avatar_face{
    border-radius: 100%;
    width: 60px;
    height: 60px;
    overflow: hidden;
}
.avatar_greet{
    margin: 20px auto;
    font-size: 20px;
    font-weight: 340;
    color: rgb(157, 161, 173);
}
.avatar_title{
    margin: 0px auto;
    font-size: 28px;
    font-weight: 600;
    color: rgb(0, 23, 51);
}

</style>
