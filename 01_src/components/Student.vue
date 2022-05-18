<template>
  <div>
      <h1>{{msg}}</h1>
      <h2>姓名：{{name}}</h2>
      <h2>年龄：{{age}}</h2>
      <h2>性别：{{sex}}</h2>

  </div>
</template>

<script>
export default {
    name:'Student',
    data(){
        return {msg:'这里是一段消息'}
    },
    props:['name','age','sex']
}
</script>

<style>

</style>