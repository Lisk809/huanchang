<script setup lang="ts"></script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <div class="downloads">
      <button class="download" type="button" @click="">
        <a href="https://apps.apple.com/cn/app/id1610091878" target="_blank"
          >App Store</a
        >
      </button>
      <button class="download" type="button" @click="">
        <a
          href="https://l.taptap.cn/FbqHpBUr?channel=rep-rep_mri1mler90h"
          target="_blank"
          >Tap Tap</a
        >
      </button>
    </div>
    <p><span class="text">幻场</span>, 发现可爱好友！</p>
  </div>
</template>

<style scoped>
.card {
  /*display: flex;*/
}
.text {
  color: #0f2c30;
  font-size: 2em;
}
.downloads {
  display: flex;
  justify-content: center;
  column-gap: 10px;
}
.download {
  /*border: #999 2px solid;*/
}
</style>
