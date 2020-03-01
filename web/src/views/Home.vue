<template>
  <div class="home">
    <app-bar left="" right="bell" />
    <avatar/>
    <tabbar/>
    <course-list/>
  </div>
</template>

<script>
import AppBar from '../components/AppBar.vue'
import Avatar from '../components/Avatar.vue'
import TabBar from '../components/TabBar.vue'
import CourseList from '../components/CourseList.vue'
export default {
  components:{
    "app-bar":AppBar,
    "avatar":Avatar,
    "tabbar":TabBar,
    "course-list":CourseList,
    
  },
}
</script>

<style>

</style>
