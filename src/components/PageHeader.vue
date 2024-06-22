<script setup lang="ts">
import '@mdui/icons/article.js'
</script>

<template>
  <mdui-top-app-bar>
    <mdui-button-icon><img style="height: 40px;width: 40px;" src="@/assets/spcraft.png"></mdui-button-icon>
    <mdui-top-app-bar-title scroll-behavior="hide" scroll-threshold="30"
      >风雨阁Storm Pavilion</mdui-top-app-bar-title
    >
    <div style="flex-grow: 1"></div>
    <a href="https://docs.spcraft.cn" target="_blank">
      <mdui-button-icon>
        <mdui-icon-article></mdui-icon-article>
      </mdui-button-icon>
    </a>
  </mdui-top-app-bar>
</template>
