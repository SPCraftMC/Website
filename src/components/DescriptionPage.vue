.<template>
    <div class="description-box">
        <h1>关于</h1>
        <p>
            风雨阁Storm Pavilion 是一个公益性质的 Minecraft 服务器。风雨阁Storm Pavilion 主要玩法为纯净生存。<br>
            服务器始终不与 Minecraft 版本 脱节， 风雨阁 Storm Pavilion 会时刻保持服务器版本为最新。<br>
            <br>
            风雨阁Storm Pavilion 最早起始于 2021 年。<br>
            一路走来，我们从最开始的纯净生存，到探索粘液科技，再回归初心，归来仍是纯净生存。<br>
            愿你玩 Minecraft 半生，归来仍是纯净生存。<br>
            <br>
            在全新的版本中，风雨阁 Storm Pavilion 化繁为简，去除复杂的 2FA 验证模式，阁下只需要一个外置登录账户/基岩版账户即可畅游服务器。<br>
            感谢 <a href="https://mcskin.cn/">红石皮肤站</a>，提供了外置登录服务器。<br>
        </p>
        <p>风雨阁Storm Pavilion 由 <span class="❤">❤</span> 驱动。</p>

        <h1>游戏内实景展示</h1>
        <div class="description-flex">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f76e8d606.webp">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f78e2986d.webp">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f791d8bd2.webp">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f81879dfb.webp">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f82aaecbf.webp">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f85ca984c.webp">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f879be852.webp">
            <img src="https://apac-cloudflare-r2-img.1l1.icu/2024/06/30/6680f8a92aea9.webp">
        </div>

        <h1>加入我们</h1>
        <p class="buttons">
            <a href="https://qm.qq.com/q/lBLowcKJ56">
                <mdui-button style="background-color: lightgreen;">加入我们</mdui-button>
            </a>
            <a href="https://docs.spcraft.cn" target="_blank">
                <mdui-button style="background-color: #66ccff;">文档中心</mdui-button>
            </a>
        </p>

        <p>
            <br>
            风雨阁 Storm Pavilion 保留所有权利。<br>
            "Minecraft"及其产品为 Mojang AB 的商标。本服务器(组织)不隶属于 Mojang AB。<br>
            本服务器在遵守 <a href="https://www.minecraft.net/eula" target="_blank">《Minecraft EULA》(最终用户许可协议) </a>的情况下运营。<br>
            本服务器不包含任何内购产品。<br>
            <br>
        </p>

        <p class="moeicp-description">
            <a href="https://icp.gov.moe/?keyword=20229960" target="_blank">萌ICP备20229960号</a>
        </p>
    </div>
</template>

<style scoped>
.description-box {
    padding: 2rem;
}

@media screen and (min-width: 700px) {
    .moeicp-description {
        display: none;
    }

    /* .footer {
        height: 300px;
    } */
}

.description-flex {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    width: 100%;
}

.description-flex img {
    max-width: 700px;
    margin: 5px;
}

@media screen and (max-width: 700px) {
    .description-flex img {
        max-width: 95%;
        margin: 5px;
    }
}

</style>
