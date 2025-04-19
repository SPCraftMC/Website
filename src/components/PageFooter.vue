<template>
    <mdui-bottom-app-bar scroll-behavior="hide" class="footer">
        <p>
            Copyright © 2021-{{ nowYear }} 风雨阁Storm Pavilion 版权所有。<br>
            <a href="https://tos-eula.spcraft.cn/" target="_blank">风雨阁 Storm Pavilion 《服务条款及最终用户许可协议》</a><br>
        </p>
        <div style="flex-grow: 1"></div>
        <p class="moeicp-right">
            <a href="https://icp.gov.moe/?keyword=20229960" target="_blank">萌ICP备20229960号</a>
        </p>
        <p class="icp-right">
            <a href="https://beian.miit.gov.cn/" target="_blank">浙ICP备2025151652号-2</a>
        </p>
    </mdui-bottom-app-bar>
</template>

<script setup lang="ts">
var nowYear = new Date().getFullYear();
</script>

<style scoped>
.footer {
    font-size: small;
}

/* .footer {
    height: 150px;
} */

@media screen and (max-width: 700px) {
    .moeicp-right {
        display: none;
    }

    /* .footer {
        height: 300px;
    } */
}
</style>
