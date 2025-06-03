<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>欢迎访问DSJIE_工作室导航页</title>
    <!-- 如果需要引入外部CSS或JS，可以在这里添加 -->
    <style>
        /* 全局样式 */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f6f9;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            /* min-height: 100vh; */
        }

        /* 容器样式 */
        .container {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            /* max-width: 500px; */
            width: 80%;
            margin-top: 10px;
        }

        /* 标题样式 */
        h1 {
            color: #333333;
            margin-bottom: 20px;
        }

        /* 按钮容器 */
        .button-group {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            margin-top: 30px;
        }

        /* 按钮样式 */
        .navigate-button {
            padding: 15px 30px;
            font-size: 16px;
            color: #ffffff;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        .navigate-button:hover {
            background-color: #0056b3;
            transform: translateY(-2px);
        }

        /* 响应式设计 */
        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }

            .navigate-button {
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>欢迎访问DSJIE_工作室导航页</h1>
        <p>请在以下选项中选择您要前往的页面：</p>
    </div>
    <div class="container">
        <h1>1.《DSJIE_工作室_博客》</h1>
        <p>所有你想了解的官网信息都在这里！</p>
        <div class="button-group">
            <a href="http://www.dsjie375.cn:8090" target="_blank">
                <button class="navigate-button">点我前往</button>
            </a>
        </div>
    </div>


    <div class="container">
        <h1>2.《云存储 DSJIE-NAS》</h1>
        <p>如果你想使用我的云存储可以免费加入共享（安卓、苹果、win、等等）</p>
        <div class="button-group">
            <a href="http://www.dsjie375.cn:9999" target="_blank">
                <button class="navigate-button">点我前往</button>
            </a>
        </div>
    </div>

    <div class="container">
        <h1>3.《原神启动》</h1>
        <p>打开原神的启动页面，还有语音：（原神，启动），之后进入一个提瓦特大陆</p>
        <div class="button-group">
            <a href="https://dsj375.github.io/op/" target="_blank">
                <button class="navigate-button">点我前往</button>
            </a>
        </div>
    </div>
    <div class="container">
        <h1>4.《Girlfriends_In》</h1>
        <p>你的女朋友都在这里。（来自GitHub开源大佬的制作）</p>
        <div class="button-group">
            <a href="https://dsj375.github.io/Girlfriends_In_HTML-main/" target="_blank">
                <button class="navigate-button">点我前往</button>
            </a>
        </div>
    </div>
    <div class="container">
        <h1>5.《隐藏的OP》</h1>
        <p>有隐藏的彩蛋</p>
        <div class="button-group">
            <a href="https://dsj375.github.io/yincangdeOP/index.html" target="_blank">
                <button class="navigate-button">点我前往</button>
            </a>
        </div>
    </div>
    
</body>

</html>
