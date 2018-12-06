<template>
  <div id="app">
      我是首页
      <button @clikc="topage(1)">点击跳到产品页面</button>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
    }
  },
  methods: {
      topage(inx){
          console.log(inx)
          location.href = "../detail/detail.html";
      }
  }
}
</script>


<style lang="scss" scoped>
 #app{
     height: 600px;
     background-color: red;
 }
</style>