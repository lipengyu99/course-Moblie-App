<template>
    <div class="TabBar">
        <el-tabs v-model="activeName"
           >
            <el-tab-pane v-for="item in items"
                :key="item.key"
                :label = "item.label"
                :name="item.id">
            
            </el-tab-pane>
        </el-tabs>
        
    </div>
</template>

<script>
export default {
data() {
    return {
        activeName:'',
        items:[
            {   
                id:"1",
                label:'Terbaru'
            },
            {
                id:"2",
                label:'Pupuler'
            },
            {
                 id:"3",
                label:'Rekomendasi'
            },

        ]
    }
},
}
</script>

<style scope>
.TabBar{
    padding: 0 20px;
}
.el-tabs__active-bar{
    background-color: rgb(43, 31, 94) !important;
}
.el-tabs__nav-wrap::after{
    background-color: transparent !important;
}
.el-tabs__item {
    color: rgb(0, 18, 41) !important;
}
</style>
