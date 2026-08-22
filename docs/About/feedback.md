# 留言

哈喇两句？或者告诉我哪里有问题？

<link rel="stylesheet" href="https://unpkg.com/@waline/client@v3/dist/waline.css"/>

<div id="waline"></div>

<script type="module">
        // 从 CDN 导入 init 函数
        import { init } from 'https://unpkg.com/@waline/client@v3/dist/waline.js';

        // 初始化 Waline
        init({
            // 必填：容器元素的选择器[reference:0][reference:1]
            el: '#waline',
            // 必填：你的 Waline 服务端地址[reference:2][reference:3]
            serverURL: 'https://wcm.catp.cc',
            // --- 以下是常用可选配置 ---
            // path: window.location.pathname, // 区分不同文章页面的路径，默认是当前路径[reference:4]
            // lang: 'zh-CN',                  // 界面语言，默认自动检测
            pageview: true,                 // 是否启用浏览量统计[reference:5]
            comment: true,                  // 是否启用评论数统计[reference:6]
        });
    </script>