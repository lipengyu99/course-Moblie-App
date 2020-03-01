<template>
   
      <el-input 
      class="search"
        placeholder="搜索"
        clearable
        suffix-icon="el-icon-search"
        v-model="input1">
    </el-input>
  
</template>

<script>

export default {
   data() {
       return {
           input1:''
       }
   },
}
</script>

<style lang="scss" scope>
.search{
    margin-top:10px;
   
}
.el-input__inner{
    border-radius: 30px !important;
     background-color: rgb(246, 245, 250) !important;
}
.el-input__icon{
    color: rgb(25, 40, 64);
    font-weight: 600 !important;
}
  

</style>
