<template>
    <div class="myTitle">教务管理系统</div>  
    <el-button type="danger" :icon="Delete" circle />
    <el-button type="warning">Warning</el-button>
    <el-button type="danger">Danger</el-button>
<div>姓名：{{name }}年龄：{{age}}性别：{{ sex }}</div>
<button v-on:click="sayHello">点我</button>
<el-button type="warning" :icon="Star" circle />
  <el-carousel height="200px">
    <el-carousel-item>
      <img src="/src/assets/1.jpg" style="width:100%;height:100%;object-fit:cover"/>
    </el-carousel-item>
    <el-carousel-item>
      <img src="/src/assets/2.jpg" style="width:100%;height:100%;object-fit:cover"/>
    </el-carousel-item>
    <el-carousel-item>
      <img src="/src/assets/3.jpg" style="width:100%;height:100%;object-fit:cover"/>
    </el-carousel-item>
  </el-carousel>
</template>

<script setup>
const name = '111'
const age = 2
const sex = '3'

function sayHello() {
  console.log('点击了按钮')
}

import {
  Check,
  Delete,
  Edit,
  Message,
  Search,
  Star
} from '@element-plus/icons-vue'
</script>
