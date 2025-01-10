<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人网页</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #555;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0 15px;
        }
        nav a:hover {
            background-color: #777;
        }
        .content {
            padding: 20px 0;
        }
        .content h2 {
            color: #333;
        }
        .content p {
            line-height: 1.6;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>欢迎来到我的个人网页</h1>
        </header>
        <nav>
            <a href="#about">关于我</a>
            <a href="#skills">技能</a>
            <a href="#projects">项目</a>
            <a href="#contact">联系我</a>
        </nav>
        <div class="content" id="about">
            <h2>关于我</h2>
            <p>你好，我是一名热爱编程和设计的开发者。我热衷于学习新技术，并且喜欢将创意转化为实际的项目。在业余时间，我喜欢阅读、旅行和摄影。</p>
        </div>
        <div class="content" id="skills">
            <h2>技能</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Python</li>
                <li>Java</li>
            </ul>
        </div>
        <div class="content" id="projects">
            <h2>项目</h2>
            <p>这里展示了一些我参与的项目：</p>
            <ul>
                <li>个人博客网站</li>
                <li>在线商店管理系统</li>
                <li>移动应用原型设计</li>
            </ul>
        </div>
        <div class="content" id="contact">
            <h2>联系我</h2>
            <p>如果你对我的项目感兴趣或有任何合作机会，欢迎通过以下方式联系我：</p>
            <p>Email: your_email@example.com</p>
            <p>电话: 123-456-7890</p>
        </div>
        <footer>
            <p>版权所有 &copy; 2025 我的个人网页</p>
        </footer>
    </div>
</body>
</html>
