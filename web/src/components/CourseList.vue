<template>
    <div class="course-list">
       <ul >
           <li v-for="i in 3" :key="i">
               <course-card/>
           </li>
       </ul>
    </div>
</template>

<script>
import CourseCard from './CourseCard.vue'
export default {
    components:{
        "course-card":CourseCard,
    }
}
</script>

<style lang="scss">
.course-list{
    padding: 0 20px;
     justify-content: center;
    align-items: center;
    height: 350px;
    transition: all .5s ease;

    ul,li{
        display: flex;
        flex: 1;
        list-style: none;
        transition: transform 0.5s ease;
    }
}

</style>
