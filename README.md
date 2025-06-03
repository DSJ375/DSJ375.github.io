<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>导航网站</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav li {
            flex: 1;
        }
        nav a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 0;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="http://www.dsjie375.cn:8090" target="_blank">DSJIE工作室博客</a></li>
            <li><a href="https://www.example.com" target="_blank">示例网站</a></li>
            <li><a href="https://www.github.com" target="_blank">GitHub</a></li>
            <!-- 添加更多链接 -->
        </ul>
    </nav>
</body>
</html>
