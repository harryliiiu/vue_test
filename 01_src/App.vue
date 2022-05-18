<template>
  <div>
    <Student name="张三" age="15" sex="男"></Student>
    <hr>
    <Student name="李四" age="24" sex="女"></Student>
    <hr>
    <Student name="王五" age="32" sex="男"></Student>
  </div>
</template>

<script>
import Student from './components/Student.vue';
export default {
    components: { Student }
}
</script>

<style>

</style>