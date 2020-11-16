
<div align="center">
  <img src="./web.svg" width="200" alt="logo" />
  <h1>lucky-canvas 抽奖插件</h1>
  <p>一个基于 JavaScript 的 ( 大转盘 / 九宫格 ) 抽奖插件</p>
  <p class="hidden">
    <a href="https://github.com/luckdraw/web-luck-draw#readme">简体中文</a>
    ·
    <a href="https://github.com/luckdraw/web-luck-draw/tree/master/en">English</a>
  </p>
  <p>
    <a href="https://github.com/luckdraw/web-luck-draw/stargazers" target="_black">
      <img src="https://img.shields.io/github/stars/luckdraw/web-luck-draw?&logo=github" alt="stars" />
    </a>
    <a href="https://github.com/luckdraw/web-luck-draw/network/members" target="_black">
      <img src="https://img.shields.io/github/forks/luckdraw/web-luck-draw?logo=github" alt="forks" />
    </a>
    <a href="https://www.npmjs.com/package/web-luck-draw" target="_black">
      <img src="https://img.shields.io/github/package-json/v/luckdraw/web-luck-draw?&logo=npm" alt="version" />
    </a>
    <a href="https://www.npmjs.com/package/web-luck-draw" target="_black">
      <img src="https://img.shields.io/npm/dm/web-luck-draw?&logo=npm" alt="downloads" />
    </a>
    <a href="https://github.com/luckdraw/web-luck-draw/tree/master/dist" target="_black">
      <img src="https://img.shields.io/github/size/luckdraw/web-luck-draw/dist/web-luck-draw.umd.min.js?&logo=npm" alt="size" />
    </a>
  </p>
  <p>
    <a href="https://github.com/buuing" target="_black">
      <img src="https://img.shields.io/badge/Author-%20buuing%20-7289da.svg?&logo=github" alt="author" />
    </a>
    <a href="https://github.com/luckdraw/web-luck-draw/blob/master/LICENSE" target="_black">
      <img src="https://img.shields.io/github/license/luckdraw/web-luck-draw?&logo=github" alt="license" />
    </a>
  </p>
</div>

<br />

## 官方文档 & Demo演示

> **中文**：[https://100px.net/document/js.html](https://100px.net/document/js.html)  

> **English**：**If anyone can help translate the document, please contact me** `ldq404@qq.com`

<br />

## 在 JavaScript 中使用

### 方式 1：通过 script 标签引入

从下面的链接里下载一个叫`web-luck-draw.umd.min.js`的 js 文件, 然后使用 script 标签引入

- [https://github.com/luckdraw/web-luck-draw/tree/master/dist](https://github.com/luckdraw/web-luck-draw/tree/master/dist)

```html
<div id="my-lucky" style="width: 300px; height: 300px"></div>
<script src="./web-luck-draw.umd.min.js"></script>
<script>

  // 大转盘抽奖
  let luckyWheel = new LuckDraw.LuckyWheel('#my-lucky', {
    // ...你的配置
  })
  
  // 九宫格抽奖
  let luckyGrid = new LuckDraw.LuckyGrid('#my-lucky', {
    // ...你的配置
  })

</script>
```

## 在 vue2.x / vue3.x 中使用

> 跳转：[vue-luck-draw](https://github.com/luckdraw/vue-luck-draw#readme)
