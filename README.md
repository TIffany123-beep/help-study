# help-studybody {
    font-family: "Microsoft JhengHei", sans-serif;
    margin: 0;
    background: url("img/bg.jpg") no-repeat center/cover fixed;
    color: #333;
}

header {
    background: rgba(0, 0, 0, 0.6);
    color: white;
    padding: 20px;
    text-align: center;
}

header img {
    height: 60px;
    animation: fadeIn 2s ease;
}

nav {
    background: #222;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: #4A90E2;
}

.container {
    max-width: 900px;
    margin: auto;
    padding: 20px;
}

.card {
    background: rgba(255, 255, 255, 0.9);
    padding: 20px;
    margin-top: 20px;
    border-radius: 10px;
    animation: slideUp 0.8s ease;
}

/* CSS 動畫 */
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

@keyframes slideUp {
    from { transform: translateY(20px); opacity: 0; }
    to { transform: translateY(0); opacity: 1; }
}

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 30px;
}
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <title>關於我</title>
</head>
<body>

<header>
    <img src="img/logo.png" alt="Logo">
    <h1>關於我</h1>
</header>

<nav>
    <a href="index.html">首頁</a>
    <a href="about.html">關於我</a>
    <a href="study.html">學習內容</a>
    <a href="diary.html">學習紀錄</a>
</nav>

<div class="container">
    <div class="card">
        <h2>我是一位熱愛學習的人</h2>
        <p>我希望能記錄學習內容，並持續成長。</p>
    </div>
</div>

<footer>© 2025 我的學習網站</footer>
</body>
</html><!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <title>學習內容</title>
</head>
<body>

<header>
    <img src="img/logo.png" alt="Logo">
    <h1>學習內容</h1>
</header>

<nav>
    <a href="index.html">首頁</a>
    <a href="about.html">關於我</a>
    <a href="study.html">學習內容</a>
    <a href="diary.html">學習紀錄</a>
</nav>

<div class="container">
    <div class="card">
        <h2>目前在學習</h2>
        <ul>
            <li>HTML / CSS / JavaScript</li>
            <li>AI 與 ChatGPT</li>
            <li>網站設計</li>
        </ul>
    </div>
</div>

<footer>© 2025 我的學習網站</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="style.css">
    <title>每日學習紀錄</title>
</head>
<body>

<header>
    <img src="img/logo.png" alt="Logo">
    <h1>每日學習紀錄</h1>
</header>

<nav>
    <a href="index.html">首頁</a>
    <a href="about.html">關於我</a>
    <a href="study.html">學習內容</a>
    <a href="diary.html">學習紀錄</a>
</nav>

<div class="container">
    <div class="card">
        <h2>2025 年 學習紀錄</h2>
        <p>📝 你可以在這裡每天寫下一點：今天學到了什麼？進步了什麼？</p>

        <ul>
            <li><strong>12/01：</strong> 學會 HTML 架構。</li>
            <li><strong>12/02：</strong> 製作多頁面網站。</li>
            <li><strong>12/03：</strong> 加入 CSS 動畫。</li>
        </ul>
    </div>
</div>

<footer>© 2025 我的學習網站</footer>
</body>
</html>

