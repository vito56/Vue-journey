<!-- 1.模板：html结构 -->
<template>
  <div id="app">
    <ul>
      <li><router-link to='/'>Home</router-link></li>
      <li><router-link to='/helloworld'>Hello</router-link></li>
      <!-- <li><a href="/">Home</a></li>
      <li><a href="/helloworld">Hello</a></li> -->
      <!-- a标签每次点击都会重新加载 -->
    </ul>
    <router-view></router-view>
  </div>
</template>


<!-- 2.行为：处理逻辑 -->
<script>

export default {
  name: 'app',
  data(){
    return{
      
    }
  }
}
</script>

<!-- 3.样式：解决样式 -->
<style scoped>
h1{
  color: purple;
}

</style>










