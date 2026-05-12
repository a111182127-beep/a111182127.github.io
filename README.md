<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>陳畹情 Panda | 數位作品集</title>
    <style>
        :root {
            --deep-ocean: #003366;
            --wave-blue: #0077be;
            --light-blue: #e3f2fd;
            --bg-color: #f4f9f9;
        }
        body { font-family: 'PingFang TC', 'Microsoft JhengHei', sans-serif; line-height: 1.8; color: #333; margin: 0; background-color: var(--bg-color); scroll-behavior: smooth; }
        
        nav { background-color: var(--deep-ocean); position: sticky; top: 0; z-index: 1000; display: flex; justify-content: center; flex-wrap: wrap; padding: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.2); }
        nav a { color: white; text-decoration: none; padding: 10px 15px; margin: 5px; border-radius: 5px; transition: 0.3s; font-size: 0.9em; }
        nav a:hover { background-color: var(--wave-blue); }

        .container { max-width: 1000px; margin: 40px auto; padding: 0 20px; }
        
        .section-box { background: white; padding: 30px; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.05); margin-bottom: 40px; }
        .section-title { color: var(--deep-ocean); border-bottom: 3px solid var(--wave-blue); padding-bottom: 10px; margin-bottom: 20px; font-size: 1.5em; display: flex; align-items: center; }
        .section-title::before { content: '⚓'; margin-right: 10px; font-size: 1.2em; }
        
        /* 內嵌框架容器：讓內容可以自適應高度 */
        .embed-container { position: relative; width: 100%; height: 500px; border: 2px solid var(--light-blue); border-radius: 10px; overflow: hidden; background: #fff; margin-top: 15px; }
        iframe { width: 100%; height: 100%; border: none; }

        .profile-header { text-align: center; margin-bottom: 20px; }
        .profile-icon { font-size: 60px; display: block; }
        
        .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; }
        @media (max-width: 600px) { .grid-2 { grid-template-columns: 1fr; } .embed-container { height: 350px; } }
        
        footer { text-align: center; padding: 40px; background: var(--deep-ocean); color: white; font-size: 0.9em; }
    </style>
</head>
<body>

    <nav>
        <a href="#home">關於我</a>
        <a href="#0309">旅遊試算表</a>
        <a href="#0316">旅遊簡報</a>
        <a href="#0323">AI作品PDF</a>
        <a href="#0330">AI旅遊影片</a>
    </nav>

    <div class="container">

        <div id="home" class="section-box profile-header">
            <span class="profile-icon">🐼</span>
            <h1>陳畹情 Panda</h1>
            <p>國立高雄科技大學 航海科 | A111182127</p>
            <p>「對大海充滿好奇，勇於跳脫舒適圈。」</p>
        </div>

        <div id="0309" class="section-box">
            <h2 class="section-title">0309 旅遊規劃試算表</h2>
            <div class="embed-container">
                <iframe src="https://docs.google.com/spreadsheets/d/12xOZfWy7ldSt7jFnzCCh8LKUDenRL_bhcDxyEzS4i9g/preview"></iframe>
            </div>
        </div>

        <div id="0316" class="section-box">
            <h2 class="section-title">0316 旅遊規畫簡報</h2>
            <div class="embed-container">
                <iframe src="https://docs.google.com/presentation/d/1qv4ccJ5Is7mo8AQKFPR14nXZGvkE0ktgptC1TqjZ61w/embed?start=false&loop=false&delayms=3000"></iframe>
            </div>
        </div>

        <div id="0323" class="section-box">
            <h2 class="section-title">0323 AI 應用作品 (PDF)</h2>
            <p>下方為 Gamma 生成之作品預覽：</p>
            <div class="embed-container">
                <iframe src="https://drive.google.com/file/d/1O4b55k7oRKVg9Uql5QO0q2ys4-z_RTBh/preview"></iframe>
            </div>
        </div>

        <div id="0330" class="section-box">
            <h2 class="section-title">0330 AI 旅遊影片</h2>
            <div class="embed-container">
                <iframe src="https://drive.google.com/file/d/1kt1a4tMF4NnPvf311MxXHqb7DknpMP7m/preview"></iframe>
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 陳畹情 (Panda). 國立高雄科技大學 航海科</p>
    </footer>

</body>
</html>
