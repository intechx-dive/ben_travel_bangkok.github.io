<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>バンコク旅行プレゼンテーション</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
                      font-size: 16px;
        }
        header {
            background: linear-gradient(to right, #fbb034, #ffdd00);
            color: white;
            text-align: center;
            padding: 2rem 0;
                      font-size: 1.5rem; 
        }
        nav {
            background: #ffdd00;
            display: flex;
            justify-content: center;
            padding: 0.5rem 0;
        }
        nav a {
            color: #333;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            color: #fbb034;
        }
        section {
            padding: 2rem;
        }
        .hero {
            background-image: <img src="Images/Bangkok_header.jpg" alt="ワット・プラケオ" >
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            background: rgba(0, 0, 0, 0.5);
            padding: 1rem;
        }
        .container {
            align-items: center;
            justify-content: center;
            max-width: 1100px;
            margin: 0 auto;
        }
        .attractions, .food {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
        }
        .card {
            flex: 1 1 calc(33.333% - 2rem);
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            background: white;
        }
        .card img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }
        .card h3 {
            margin: 1rem;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #fbb034;
            color: white;
        }
    </style>
</head>
<body>

<header>
    <h1>バンコクを探検しよう</h1>
    <p>タイの心臓部へようこそ</p>
</header>

<nav>
    <a href="#introduction">紹介</a>
    <a href="#attractions">観光名所</a>
    <a href="#food">食文化</a>
    <a href="#tips">旅行のヒント</a>
</nav>

</section>

<section id="introduction" class="container">
    <div align="center">
    <img src="Images/Bangkok_header.jpg" alt="Bangkok_header" width="full" height="full" "align-items: center">
    <h2>紹介</h2>
    <p>バンコクはタイの首都であり、伝統と現代が融合した都市です。活気あるストリートライフ、アイコニックな寺院、美味しい食べ物で知られています。観光客にとって忘れられない体験を提供します。</p>
</section>

<section id="attractions" class="container">
    <h2>観光名所</h2>
    <div class="attractions">
        <div class="card">
            <img src="Images/grand_palace.jpg" alt="ワット・プラケオ" width="400px" height="250px">
            <h3>ワット・プラケオ (エメラルド寺院)</h3>
            <p>タイの象徴であるエメラルド仏像を所蔵する歴史的な寺院。</p>
        </div>
        <div class="card">
            <img src="Images/wat_arun.jpg" alt="watarun"  width="400px" height="250px">
            <h3>ワット・アルン (暁の寺)</h3>
            <p>チャオプラヤ川のほとりに位置する美しい寺院。日の出や日没時が最適。</p>
        </div>
        <div class="card">
            <img src="Images/chatuchak_market.png" alt="チャトチャック市場" width="400px" height="250px">
            <h3>チャトチャック週末市場</h3>
            <p>世界最大級の市場で、15,000以上の屋台が並びます。</p>
        </div>
    </div>
</section>

<section id="food" class="container">
    <h2>バンコクの食文化</h2>
    <div class="food">
        <div class="card">
            <img src="Images/tomyum.png" alt="tomyum"  width="500px" height="400px">
	    <h3>トムヤム</h3>
            <img src="Images/padthai.jpg" alt="padthai"  width="500px" height="400px">
            <h4>パッタイ</h4>
            <img src="Images/kapao.jpg" alt="kapao"  width="500px" height="400px">
	    <h5>カパオ</h5>
	    <img src="Images/Green_curry.jpg" alt="Green_curry"  width="500px" height="400px">
	    <h5>グリーンカレー</h5>
            <p></p>
        </div>
        <div class="card">
            <img src="Images/sky_bar.png" alt="sky_bar"  width="350px" height="300px">
　　　　　　 <h3>シロッコ・スカイバー</h3>
            <img src="Images/moon_bar.png" alt="moon_bar"  width="350px" height="300px">
            <h3>ムーンバー</h3>
            <img src="Images/Sky.png" alt="Sky"  width="350px" height="300px">
            <h3>スカイバー</h3>
            <img src="Images/Three Sixty.png" alt="Three Sixty"  width="350px" height="300px">
            <h3>スリーシックスティーミレニアム</h3>


            <p></p>
        </div>
    </div>
</section>

<section id="tips" class="container">
    <h2>旅行のヒント</h2>
    <ul>
        <li><strong>おすすめの訪問時期:</strong> 11月から2月 (涼しくて乾燥した季節)。</li>
        <li><strong>交通手段:</strong> BTSスカイトレイン、MRT地下鉄、またはトゥクトゥクで移動。</li>

    </ul>
</section>

<footer>
    <p>今日からバンコクの旅を計画しましょう！</p>
</footer>

</body>
</html>
