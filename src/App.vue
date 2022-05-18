<template>
  <div>
    <MyHeader></MyHeader>
    <MyList></MyList>
    <MyFooter></MyFooter>
  </div>
</template>

<script>
  import MyHeader from './components/MyHeader.vue'
  import MyFooter from './components/MyFooter.vue'
  import MyList from './components/MyList.vue'
  export default {
    name:'App',
    comments:{MyHeader,MyFooter,MyList}
  }
</script>

<style>

</style>