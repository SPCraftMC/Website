<template>
    <mdui-bottom-app-bar scroll-behavior="hide" class="footer">
        <p>
            Copyright © 2021-{{ nowYear }} 风雨阁Storm Pavilion 版权所有。<br>
            <a href="https://tos-eula.spcraft.cn/" target="_blank">风雨阁 Storm Pavilion 《服务条款及最终用户许可协议》</a><br>
            <a href="https://icp.gov.moe/?keyword=20229960" target="_blank">萌ICP备20229960号</a>
        </p>
        <div style="flex-grow: 1"></div>
        <p>
            <br>
            风雨阁 Storm Pavilion 保留所有权利。<br>
            "Minecraft"及其产品为 Mojang AB 的商标。本服务器(组织)不隶属于 Mojang AB。<br>
            本服务器在遵守 <a href="https://www.minecraft.net/eula" target="_blank">《Minecraft EULA》(最终用户许可协议) </a>的情况下运营。<br>
            本服务器不包含任何内购产品。<br>
            <br>
        </p>
    </mdui-bottom-app-bar>
</template>

<script setup lang="ts">
var nowYear = new Date().getFullYear();
</script>

<style scoped>
.footer {
    height: 150px;
}

@media screen and (max-width: 700px) {
    .footer {
        height: 300px;
    }
}
</style>
