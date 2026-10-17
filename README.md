<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K-POP 女團魅力大解析</title>
    <!-- 引入 Google Fonts 與 Bootstrap 5 樣式 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans TC', sans-serif;
            background-color: #f8f9fa;
            color: #333;
        }
        .hero-section {
            background: linear-gradient(135deg, #ff758c 0%, #ff7eb3 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
        }
        .card {
            border: none;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-radius: 15px;
            overflow: hidden;
        }
        .card:hover {
            transform: translateY(-8px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.15);
        }
        .card-img-top {
            height: 220px;
            object-fit: cover;
        }
        .footer {
            background-color: #343a40;
            color: white;
            padding: 30px 0;
            text-align: center;
        }
    </style>
</head>
<body>

    <!-- 導覽列 -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">✨ K-POP Girl Groups</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link" href="#groups">人氣女團</a></li>
                    <li class="nav-item"><a class="nav-link" href="#features">曲風特色</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">聯絡我們</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- 網頁標頭 (Hero Section) -->
    <header class="hero-section">
        <h1 class="fw-bold">探索風靡全球的韓流魅力</h1>
        <p class="lead mt-2">帶你認識引領潮流與時尚的頂尖女子偶像團體</p>
    </header>

    <!-- 內容主容器 -->
    <div class="container my-5" id="groups">
        <h2 class="text-center fw-bold mb-4">🌟 當前最具代表性的人氣女團</h2>
        <p class="text-center text-muted mb-5">點燃全球舞台的閃耀新星與傳奇組合</p>

        <div class="row g-4">
            <!-- 團體 1: BLACKPINK -->
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1516450360452-9312f5e86fc7?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="BLACKPINK">
                    <div class="card-body">
                        <h5 class="card-title fw-bold">BLACKPINK</h5>
                        <h6 class="text-muted">YG Entertainment</h6>
                        <p class="card-text mt-3">以強烈的 Crush Girl 風格、席捲全球的百億流量 MV 以及引領國際時尚潮流聞名，是全球最具影響力的頂級女團之一。</p>
                    </div>
                </div>
            </div>

            <!-- 團體 2: (G)I-DLE -->
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1526478806334-5fd488fcaabc?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="(G)I-DLE">
                    <div class="card-body">
                        <h5 class="card-title fw-bold">(G)I-DLE</h5>
                        <h6 class="text-muted">Cube Entertainment</h6>
                        <p class="card-text mt-3">以實力派「全創作自給自足」聞名，隊長小娟帶領成員打造出《Tomboy》、《Queencard》等多首破億洗腦神曲，充滿大膽且自信的獨特風格。</p>
                    </div>
                </div>
            </div>

            <!-- 團體 3: IVE -->
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1492684223066-81342ee5ff30?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="IVE">
                    <div class="card-body">
                        <h5 class="card-title fw-bold">IVE</h5>
                        <h6 class="text-muted">Starship Entertainment</h6>
                        <p class="card-text mt-3">主打「Narcissism（自我愛戀）」的概念，以極具中毒性的旋律（如《Love Dive》、《I AM》）和高顏值席捲各大音源榜。</p>
                    </div>
                </div>
            </div>

            <!-- 團體 4: NewJeans -->
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1514525253161-7a46d19cd819?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="NewJeans">
                    <div class="card-body">
                        <h5 class="card-title fw-bold">NewJeans</h5>
                        <h6 class="text-muted">ADOR</h6>
                        <p class="card-text mt-3">掀起復古 Y2K 流行風潮的寶藏女團，以輕鬆耐聽的 Easy-Listening R&B 曲風及獨特清純自然的魅力贏得大眾喜愛。</p>
                    </div>
                </div>
            </div>

            <!-- 團體 5: aespa -->
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="aespa">
                    <div class="card-body">
                        <h5 class="card-title fw-bold">aespa</h5>
                        <h6 class="text-muted">SM Entertainment</h6>
                        <p class="card-text mt-3">開創元宇宙與 AI 概念的世界觀女團。憑藉《Next Level》、《Supernova》等前衛洗腦的強烈電子舞曲震撼樂壇。</p>
                    </div>
                </div>
            </div>

            <!-- 團體 6: LE SSERAFIM -->
            <div class="col-md-4">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1508700115892-45ecd05ae2ad?auto=format&fit=crop&w=600&q=80" class="card-img-top" alt="LE SSERAFIM">
                    <div class="card-body">
                        <h5 class="card-title fw-bold">LE SSERAFIM</h5>
                        <h6 class="text-muted">Source Music</h6>
                        <p class="card-text mt-3">以「無所畏懼（I'M FEARLESS）」為核心精神，主打高難度刀群舞與充滿力量的自信態度，展現獨樹一格的 Girl Crush 魅力。</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- 頁尾 -->
    <footer class="footer" id="contact">
        <div class="container">
            <p class="mb-0">© 2026 K-POP Girl Groups Intro. Designed for Web Design Assignment.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


