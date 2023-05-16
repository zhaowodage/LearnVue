<!-- 组件样式 -->
<template> 
    <div id='Demo'>
        <h2>学校名称：{{name}}</h2>
        <h2>学校地址：{{address}}</h2>
        <button @click="showName">点我提示学校名</button>
    </div>
</template>

<!--组件交互-->
<script>
    export default {
        name:'School',
        data() {
            return {
                name:'尚硅谷',
                address:'北京'
            }
        },
        methods: {
            showName(){
                alert(this.name)
            }
        },
    }
</script>

<!-- 组件样式 -->
<style>
    #Demo{
        background: orange;
    }
</style>
