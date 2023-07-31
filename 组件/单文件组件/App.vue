<template>
  <div>
    <School></School>
    <student></student>
  </div>
</template>

<script>
import School from './School.Vue';
import Student from './Student.vue';

export default {
    name:'App',
    components:{
        // School:School,
        // Student:Student
        // 精简：
        School,
        Student

    }
}
</script>

<style>

</style>