<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>我的跳转网站</title>
<style>
    body {
        margin: 0;
        font-family: "微软雅黑", sans-serif;
        background: linear-gradient(to right, #74ebd5, #ACB6E5);
        display: flex;
        flex-direction: column;
        align-items: center;
        min-height: 100vh;
        color: #fff;
    }
    h1 {
        margin: 40px 0 20px 0;
        font-size: 2em;
        text-shadow: 1px 1px 4px rgba(0,0,0,0.3);
    }
    .link-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
        gap: 20px;
        width: 90%;
        max-width: 1000px;
    }
    .link-grid a {
        display: block;
        text-align: center;
        padding: 15px;
        background-color: rgba(255,255,255,0.2);
        color: #fff;
        text-decoration: none;
        font-weight: bold;
        border-radius: 10px;
        transition: all 0.3s ease;
        box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }
    .link-grid a:hover {
        background-color: rgba(255,255,255,0.4);
        transform: translateY(-5px);
        box-shadow: 0 6px 10px rgba(0,0,0,0.3);
    }
    footer {
        margin: 40px 0;
        font-size: 14px;
        color: #eee;
    }
</style>
</head>
<body>

<h1>我的跳转网站</h1>

<div class="link-grid">
    <a href="https://www.baidu.com" target="_blank">91</a>
    <a href="https://www.google.com" target="_blank">约炮</a>
    <a href="https://www.youtube.com" target="_blank">海角</a>
    <a href="https://www.qq.com" target="_blank">抖阴</a>
    <a href="https://www.taobao.com" target="_blank">黄瓜</a>
    <a href="https://www.jd.com" target="_blank">秀人网</a>
    <a href="https://www.zhihu.com" target="_blank">日本av</a>
    <a href="https://www.bilibili.com" target="_blank">金典三级</a>
    <!-- 继续添加你的链接 -->
</div>

<footer>© 2026 我的跳转网站</footer>

</body>
</html>
