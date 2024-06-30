<template>
    <div class="first-screen">
        <div class="first-screen-box">
            <h1 style="font-size: 40px;">风雨阁Storm Pavilion 2</h1>
            <span style="margin: auto;">一切推倒重来，全新的版本，更好的功能体验</span>

            <br>

            <p class="buttons">
                <a href="https://qm.qq.com/q/lBLowcKJ56">
                    <mdui-button style="background-color: lightgreen;">加入我们</mdui-button>
                </a>
                <a href="https://docs.spcraft.cn" target="_blank">
                    <mdui-button style="background-color: #66ccff;">文档中心</mdui-button>
                </a>
            </p>
        </div>
    </div>
</template>

<style scoped>
.first-screen {
    transform: translate(-8px, -8px);
    position: relative;
    width: 100vw;
    height: 90vh;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    background-image: url(https://apac-cloudflare-r2.img.1l1.icu/2024/06/23/66773e9583aed.webp);
}

@media screen and (max-width: 700px) {
    .first-screen {
        height: 60vh;
    }
}

.first-screen-box {
    color: white;
    margin: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.buttons {
    margin: auto;
}
</style>
