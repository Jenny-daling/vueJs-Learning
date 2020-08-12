<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to='/mine'>我的添加</router-link> |
      <router-link :to="{name:'test1',params:{name:'zdl',age:18}}">测试子路由1</router-link> |
      <router-link to='/mine/test2'>测试子路由2</router-link> |
      <router-link to='/testUrl/5/zhangsan'>URL传参</router-link> |
      <router-link to='/xx'>重定向</router-link> |
      <router-link to='/test1alias'>alias别名</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
