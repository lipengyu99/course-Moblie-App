<template>
    <div class="app-bar">
        <span class="app-bar_l" @click="$emit('left')">
            <i class="boder" :class="['fa', `fa-${left}`]"></i>
        </span>
         <span class="app-bar_r" @click="$emit('right')">
            <i :class="['fa', `fa-${right}`]"></i>
        </span>
    </div>
</template>

<script>
export default {
    props:{
        left:{
            type:String,
            default:'chevron-left'
        },
        right:{
            type:String,
            default:'ellipsis-v'
        },
    }
}
</script>

<style>
.app-bar{
    display: flex;
    height: 34px;
    justify-content: space-between;
    margin: 20px;
    align-items: center;
    z-index: 1;
}



</style>
