<template>
  <div class="navbar">
    <router-link class="navbar-item" to="/">主页</router-link>
    <router-link class="navbar-item" to="HelloWorld">欢迎</router-link>
  </div>
</template>

<script>
  export default {
    name: 'Navbar',
    data(){
      return {

      }
    }
  }
</script>

<style>
.navbar{
  width: 100%;
  height: 80px;
  border-bottom: 1px solid #eee;
}
.navbar-item{
  font-size: 14px;
  color: #353535;
  display: inline-block;
  width: 100px;
  height: 100%;
  line-height: 80px;
  text-align: center;
  cursor: pointer;
}
.navbar-item:hover{
  background-color: #f6f6f6;
}
</style>

