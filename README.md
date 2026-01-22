<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Designer Portfolio | 简约复古</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- 导航栏 -->
    <nav class="nav-bar">
        <div class="logo">PORTFOLIO</div>
        <div class="nav-links">
            <a href="#about">ABOUT</a>
            <a href="#projects">WORK</a>
            <a href="#contact">CONTACT</a>
        </div>
    </nav>

    <!-- 首页/介绍区 -->
    <section id="about" class="hero-section">
        <div class="avatar-container">
            <img src="avatar.jpg" alt="Designer Avatar" class="avatar">
        </div>
        <div class="intro-text">
            <h1>你好，我是 [你的名字]</h1>
            <p>专注于视觉传达与品牌设计的独立设计师。坚持“少即是多”的复古美学。</p>
        </div>
    </section>

    <!-- 项目展示区 -->
    <section id="projects" class="project-section">
        <div class="filter-buttons">
            <button class="filter-btn active" data-filter="all">全部</button>
            <button class="filter-btn" data-filter="web">UI/UX</button>
            <button class="filter-btn" data-filter="brand">品牌</button>
        </div>

        <div class="project-grid">
            <!-- 项目卡片示例 -->
            <div class="project-item web" onclick="showDetail('project1')">
                <div class="project-img" style="background-color: #D1CDC7;"></div>
                <h3>现代极简网页设计</h3>
                <span>UI/UX Design</span>
            </div>
            <div class="project-item brand">
                <div class="project-img" style="background-color: #C5C1BA;"></div>
                <h3>复古咖啡厅视觉系统</h3>
                <span>Branding</span>
            </div>
        </div>
    </section>

    <!-- 联系区 -->
    <section id="contact" class="contact-section">
        <h2>让我们聊聊合作</h2>
        <p>Email: <a href="mailto:hello@designer.com">hello@designer.com</a></p>
        <div class="social-links">
            <a href="#">Instagram</a> / <a href="#">Behance</a> / <a href="#">Dribbble</a>
        </div>
    </section>

    <!-- 简易项目详情弹窗 (模拟详情页) -->
    <div id="project-modal" class="modal">
        <div class="modal-content">
            <span class="close-btn">&times;</span>
            <div id="modal-body"></div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
