<template>
    <div>
        <School></School>
        <Student></Student>
    </div>
</template>

<!-- 注册子组件 -->
<script>
    import School from './School.vue'
    import Student from './Student.vue'

    export default {
        name:'App',
        components:{
            School,
            Student
        }
    }
</script>
