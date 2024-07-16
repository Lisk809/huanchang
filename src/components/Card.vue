<script setup lang="ts"></script>

<template>

  <div class="card">
    <div class="downloads">
      <button class="download apple" type="button" @click="">
        <a href="https://apps.apple.com/cn/app/id1610091878" target="_blank">
		<img class="dlogo" src="https://www.apple.com/favicon.ico" /><p class="atext">App Store</p>
	</a>
      </button>
      <button class="download" type="button" @click="">
        <a
          href="https://l.taptap.cn/FbqHpBUr?channel=rep-rep_mri1mler90h"
          target="_blank"
          >
	  <img class="dlogo" src="https://www.taptap.cn/favicon.ico" />
	  Tap Tap</a
        >
      </button>
    </div>
    <p>
    <img class="text" src="/text.png" alt="huanchang"/>
    , 发现可爱好友！</p>
  </div>
</template>

<style scoped>
.card {
  /*display: flex;*/
}
.text {
  width: 3em;
  transform: translateY(6px)
}
.downloads {
  display: flex;
  justify-content: center;
  column-gap: 10px;
}
.download {
  display: flex;                                                        justify-content: center;
  align-items: center;
  /*border: #999 2px solid;*/
}
.atext {
  display: inline;
  color: #fff
}
.apple {
  background-color: #0B242B;
}
.dlogo {
  width:20px;
  transform: translateY(4px)
}
</style>
