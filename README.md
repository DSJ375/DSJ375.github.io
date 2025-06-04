<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>友情链接-DSJIE_工作室</title>
</head>
<body>
    <script>
        // 设置跳转的目标URL
        const targetUrl = "http://www.dsjie375.cn:8090/1748971710750";

        // 设置延迟时间（毫秒）
        const delay = 0; // 3秒

        // 使用 setTimeout 在延迟后跳转
        setTimeout(() => {
            window.location.href = targetUrl;
        }, delay);

        // 获取按钮元素
        const button = document.getElementById("jumpButton");

        // 绑定点击事件
        button.addEventListener("click", () => {
            window.location.href = targetUrl;
        });
    </script>
</body>
</html>
