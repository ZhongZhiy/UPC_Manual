<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>投稿系统测试页面</title>
    <style>
        body { font-family: sans-serif; line-height: 1.6; max-width: 800px; margin: auto; padding: 20px; background-color: #f4f4f4; }
        header { background: #2c3e50; color: white; padding: 1rem; text-align: center; }
        section { background: white; padding: 20px; margin-top: 20px; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        code { background: #eee; padding: 2px 4px; border-radius: 4px; }
        table { width: 100%; border-collapse: collapse; margin: 10px 0; }
        table, th, td { border: 1px solid #ddd; padding: 8px; text-align: left; }
        th { background-color: #f2f2f2; }
    </style>
</head>
<body>

<header>
    <h1>欢迎来到内容投稿中心</h1>
    <p><em>Version 1.0 - 语法测试版</em></p>
</header>

<nav>
    <p><b>快速导航：</b> <a href="#rules">投稿规则</a> | <a href="#form">在线投稿</a> | <a href="#contact">联系我们</a></p>
</nav>

<hr>

<section id="intro">
    <h2>关于投稿</h2>
    <p>我们需要高质量的 <strong>技术分享</strong>、<strong>生活随笔</strong> 或 <strong>创意插画</strong>。无论你是小白还是大佬，这里都有你的舞台。</p>
    <blockquote>
        “写作是思维的深度整理。” —— 匿名贡献者
    </blockquote>
</section>

<section id="rules">
    <h2>投稿要求 (列表测试)</h2>
    <ul>
        <li>内容原创，严禁剽窃。</li>
        <li>格式规范，推荐使用 <u>Markdown</u> 编写。</li>
        <li>重点词汇请使用 <code>&lt;code&gt;</code> 标签标注。</li>
    </ul>

    <h3>稿件类型说明 (描述列表测试)</h3>
    <dl>
        <dt>技术类</dt>
        <dd>包含代码实现、架构设计、算法解析等。</dd>
        <dt>文学类</dt>
        <dd>诗歌、散文或小说连载。</dd>
    </dl>
</section>

<section>
    <h2>稿酬标准 (表格测试)</h2>
    <table>
        <thead>
            <tr>
                <th>级别</th>
                <th>字数要求</th>
                <th>预计审核时间</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>初级稿件</td>
                <td>800+</td>
                <td>3 个工作日</td>
            </tr>
            <tr>
                <td>深度专栏</td>
                <td>2000+</td>
                <td>5-7 个工作日</td>
            </tr>
        </tbody>
    </table>
</section>

<section id="form">
    <h2>立即投稿 (表单测试)</h2>
    <form action="#" method="post">
        <fieldset>
            <legend>基本信息</legend>
            <p>
                <label for="username">作者昵称：</label>
                <input type="text" id="username" name="username" placeholder="请输入你的笔名" required>
            </p>
            <p>
                <label>投稿类别：</label>
                <input type="radio" id="tech" name="cate" value="tech"> <label for="tech">技术</label>
                <input type="radio" id="life" name="cate" value="life"> <label for="life">生活</label>
            </p>
            <p>
                <label for="color">选择封面主题色：</label>
                <input type="color" id="color" name="color">
            </p>
        </fieldset>

        <fieldset style="margin-top: 10px;">
            <legend>稿件正文</legend>
            <p>
                <textarea id="content" name="content" rows="5" style="width:100%;" placeholder="在此输入文章摘要..."></textarea>
            </p>
            <p>
                <label for="file">上传附件 (PDF/Zip):</label>
                <input type="file" id="file" name="file">
            </p>
        </fieldset>

        <p>
            <progress value="50" max="100"></progress> 
            <small>信息填写进度</small>
        </p>

        <button type="submit">提交稿件</button>
        <button type="reset">重置表单</button>
    </form>
</section>

<section id="media">
    <h2>多媒体测试</h2>
    <p>下方是一个占位图片测试：</p>
    <img src="https://via.placeholder.com/400x200" alt="测试占位图" style="max-width: 100%;">
    
    <p>特殊数学公式呈现（使用 <sub>下标</sub> 与 <sup>上标</sup>）：</p>
    <p>E = mc<sup>2</sup> | H<sub>2</sub>O</p>
</section>

<footer style="text-align: center; margin-top: 30px; color: #888;">
    <address id="contact">
        联系我们：<a href="mailto:test@example.com">test@example.com</a><br>
        地址：中国 · 青岛 · 黄岛区
    </address>
    <p>&copy; 2026 投稿测试中心. <time datetime="2026-05-09">2026年5月</time></p>
</footer>

</body>
</html>
