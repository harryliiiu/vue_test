<template>
    <div>
        <!-- 组件的结构 -->
        <h2 class="demo">学校姓名：{{name}}</h2>
        <h2>学校地址：{{address}}</h2>
    </div>
</template>

<script>
//组件交互使用的代码
    export default {
        name: "SchoolCom",
        data() {
            return {
                name: '华东交通大学',
                address: '广州'
            }
        }
    }
</script>


<style>
/* 组件的样式 */
.demo{
    color:blue
}
</style>