<template>
  <div class="main">
    <img
      class="logo"
      src="https://brand-1311379785.cos.ap-shanghai.myqcloud.com/icon32.png"
    />
    <p class="text">幻场</p>
    <div class="list" @click="isList=!isList">
    <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" focusable="false" viewbox="0 0 24 24" width="30" height="30" class="text_icon"><path d="M12,16c-0.3,0-0.5-0.1-0.7-0.3l-6-6c-0.4-0.4-0.4-1,0-1.4s1-0.4,1.4,0l5.3,5.3l5.3-5.3c0.4-0.4,1-0.4,1.4,0s0.4,1,0,1.4l-6,6C12.5,15.9,12.3,16,12,16z"></path></svg>
    </div>
  </div>
  <div v-if="isList" class="page">
  <div class="box">
	  <div class="li"><a href="/news">最新资讯</a></div>
	  <div class="li"><a href="/updates">近期更新</a></div>
  </div>
  </div>
</template>
<style scoped>
.main {
  position: fixed;
  top: 0px;
  left: 0px;
  right: 0px;
  height: 2px;
  width: 0%;
  opacity: 1;
  z-index: 9999;
  width: 100vw;
  height: 50px;
  background-color: #fff;
  color: #0B242B;
  display: flex;
  align-items: center;
}
.logo {
  width: 20px;
  position: absolute;
  left: 10px;
}

.text {
  position: absolute;
  left: 50px;
}
.list {
  position: absolute;
  right: 10px;
}
.page {
  position: absolute;
  top: 50px; 
  width: 100vw;
  height: 100vh;
  background: #fff;
  z-index: 999;
}
.box {
  width:100vw;
  height: 100vh;
  display: flex;
  flex-direction:column;
  row-gap: 25px;
}
.li {
  height: 30px;
  width: fix-content;
  text-align: left;
  border-style: outset none;
  border-color: #fcfcfc;
  border-width: 1px;
}
</style>
<script setup lang="ts">
import {ref} from 'vue';
var isList=ref(false)
</script>
