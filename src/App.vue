<template>
  <!--<div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>-->
  <mu-appbar title="Title">
    <mu-text-field icon="search" class="appbar-search-field"  slot="right" hintText="请输入搜索内容"/>
    <mu-flat-button color="white" label="按钮" slot="right"/>
  </mu-appbar>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style lang="less">
/*#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
.appbar-search-field{
  color: #FFF;
  margin-bottom: 0;
  &.focus-state {
    color: #FFF;
  }
  .mu-text-field-hint {
    color: fade(#FFF, 54%);
  }
  .mu-text-field-input {
    color: #FFF;
  }
  .mu-text-field-focus-line {
    background-color: #FFF;
  }
}
</style>
