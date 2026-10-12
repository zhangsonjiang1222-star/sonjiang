<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>台東美食口袋名單 | Taitung Foodie Map</title>
    <style>
        :root {
            --primary-color: #e65100;
            --secondary-color: #fff3e0;
            --bg-color: #fcfbf9;
            --text-color: #333333;
            --card-bg: #ffffff;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            color: var(--text-color);
            background-color: var(--bg-color);
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1200&q=80') center/cover;
            color: white;
            text-align: center;
            padding: 4rem 1rem;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }

        nav {
            background: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
            padding: 0.8rem 0;
            gap: 2rem;
        }

        nav a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: bold;
            transition: color 0.2s;
        }

        nav a:hover {
            color: var(--primary-color);
        }

        main {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }

        .section-title {
            font-size: 1.8rem;
            color: var(--primary-color);
            border-bottom: 3rem solid var(--secondary-color);
            line-height: 0.1;
            margin: 2.5rem 0 1.5rem 0;
        }

        .section-title span {
            background: var(--bg-color);
            padding: 0 10px;
        }

        .food-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }

        .food-card {
            background: var(--card-bg);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            transition: transform 0.2s, box-shadow 0.2s;
            display: flex;
            flex-direction: column;
        }

        .food-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
        }

        .food-info {
            padding: 1.5rem;
            flex-grow: 1;
        }

        .tag {
            display: inline-block;
            background-color: var(--secondary-color);
            color: var(--primary-color);
            font-size: 0.8rem;
            padding: 0.2rem 0.6rem;
            border-radius: 20px;
            font-weight: bold;
            margin-bottom: 0.5rem;
        }

        .food-title {
            margin: 0 0 0.5rem 0;
            font-size: 1.3rem;
        }

        .map-link {
            display: inline-block;
            margin-top: 1rem;
            color: var(--primary-color);
            text-decoration: none;
            font-weight: bold;
        }

        .map-link:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background: #333;
            color: white;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>台東在地美食口袋名單</h1>
        <p>探索東海岸的美味驚喜，從經典老店到特色咖啡廳</p>
    </header>

    <nav>
        <ul>
            <li><a href="#street-food">經典小吃</a></li>
            <li><a href="#desserts">甜點冰品</a></li>
            <li><a href="#cafe">風格咖啡館</a></li>
        </ul>
    </nav>

    <main>
        <!-- 經典小吃區塊 -->
        <section id="street-food">
            <h2 class="section-title"><span>經典小吃</span></h2>
            <div class="food-grid">
                <div class="food-card">
                    <div class="food-info">
                        <span class="tag">必吃老店</span>
                        <h3 class="food-title">卑南豬血湯</h3>
                        <p>濃郁湯頭搭配新鮮滑嫩的豬血，再加上獨門韭菜與蒜泥醬料，是台東最具代表性的在地早午餐之一。</p>
                        <p><strong>推薦菜色：</strong>豬血湯、米腸</p>
                        <a href="https://maps.google.com" target="_blank" class="map-link">📍 查看 Google 地圖</a>
                    </div>
                </div>

                <div class="food-card">
                    <div class="food-info">
                        <span class="tag">排隊美食</span>
                        <h3 class="food-title">榕樹下米苔目</h3>
                        <p>傳承多年的古早味，Q彈的米苔目淋上香噴噴的肉燥與柴魚片，攪拌均勻後每一口都充滿濃濃古早味。</p>
                        <p><strong>推薦菜色：</strong>乾米苔目、滷蛋、滷滷豆腐</p>
                        <a href="https://maps.google.com" target="_blank" class="map-link">📍 查看 Google 地圖</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- 甜點冰品區塊 -->
        <section id="desserts">
            <h2 class="section-title"><span>甜點冰品</span></h2>
            <div class="food-grid">
                <div class="food-card">
                    <div class="food-info">
                        <span class="tag">消暑首選</span>
                        <h3 class="food-title">寶桑湯圓</h3>
                        <p>手工現做的小湯圓口感極佳，無論是熱熱吃還是搭配冷碎冰都非常吸睛，紅豆與花生煮得綿密順口。</p>
                        <p><strong>推薦菜色：</strong>綜合冰湯圓</p>
                        <a href="https://maps.google.com" target="_blank" class="map-link">📍 查看 Google 地圖</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- 風格咖啡館區塊 -->
        <section id="cafe">
            <h2 class="section-title"><span>風格咖啡館</span></h2>
            <div class="food-grid">
                <div class="food-card">
                    <div class="food-info">
                        <span class="tag">文青熱點</span>
                        <h3 class="food-title">台東老宅咖啡</h3>
                        <p>將數十年老屋改建的舒適空間，提供手沖單品咖啡與每日限量手作手甜點，適合午後慢活放空。</p>
                        <p><strong>推薦菜色：</strong>手沖咖啡、戚風蛋糕</p>
                        <a href="https://maps.google.com" target="_blank" class="map-link">📍 查看 Google 地圖</a>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 台東美食地圖網站 | 作業展示專用</p>
    </footer>

</body>
</html>



