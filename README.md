<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人网站 - 一点万木易の小窝</title>
    <style>
        /* 全局样式 */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://i0.hdslb.com/bfs/article/46a9316e3bbd06d2aacf0f9669a824c3334933177.jpg@720w_402h_1e_1c.avif'); /* 替换为你的背景图片链接 */
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            color: #333;
        }

        header {
            background-color: rgba(172, 58, 207, 0.8);
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: rgba(211, 109, 109, 0.9);
            color: white;
            padding: 10px 0;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background-color: rgba(255, 255, 255, 0.3); /* 半透明背景 */
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px); /* 磨砂玻璃效果 */
            -webkit-backdrop-filter: blur(10px); /* 兼容 Safari */
        }

        footer {
            background-color: rgba(196, 63, 118, 0.9);
            color: white;
            text-align: center;
            padding: 10px;
        }

        .button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #0056b3;
        }

        /* 响应式设计 */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 10px 0;
            }

            section {
                margin: 10px;
                padding: 15px;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>一点万木易の小窝</h1>
        <p>欢迎来到我的个人网站！</p>
    </header>
    <nav>
        <ul>
            <li><a href="#home">主页</a></li>
            <li><a href="#about">关于我</a></li>
            <li><a href="#portfolio">作品展示</a></li>
            <li><a href="#contact">联系我</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2>主页</h2>
        <p>欢迎来到我的个人网站！在这里，你可以了解我的背景、查看我的作品，并通过多种方式与我联系。</p>
    </section>
    <section id="about">
        <h2>关于我</h2>
        <p>我是一个热爱编程和设计的人，致力于创造出有价值的作品。我擅长JAVA C++ or js 及前端的拼写与阅读。</p>
        <a href="https://space.bilibili.com/458203266" target="_blank" class="button">访问我的B站空间</a>
    </section>
    <section id="portfolio">
        <h2>作品展示</h2>
        <p>以下是我的一些项目作品：</p>
        <ul>
            <li>项目1：无</li>
            <li>项目2：暂无</li>
            <li>项目3：再说吧</li>
        </ul>
        <a href="https://github.com" target="_blank" class="button">查看我的GitHub</a>
    </section>
    <section id="contact">
        <h2>联系我</h2>
        <p>如果你有任何问题或合作意向，请通过以下方式联系我：</p>
        <p>邮箱：3112505527@qq.com</p>
    </section>
    <footer>
        <p>版权所有 &copy; 2025 一点万木易の小窝</p>
    </footer>
</body>

</html>
