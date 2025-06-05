<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>住宅ローン借り換えリノベーション | 株式会社ベストリンクス</title>
    <meta name="description" content="15年以上前に住宅を購入されたご家族へ。理想の住まいで、新しい暮らしを。">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Helvetica Neue', Arial, 'Hiragino Sans', 'Hiragino Kaku Gothic ProN', sans-serif;
            color: #333;
            line-height: 1.6;
            background: #f8f8f8;
        }

        /* ヘッダー（土屋鞄そっくり） */
        .header {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            background: rgba(248, 248, 248, 0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            border-bottom: 1px solid rgba(0,0,0,0.1);
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            height: 70px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .hamburger {
            display: flex;
            flex-direction: column;
            cursor: pointer;
            gap: 4px;
        }

        .hamburger span {
            width: 20px;
            height: 1px;
            background: #333;
            transition: 0.3s;
        }

        .logo {
            font-size: 18px;
            font-weight: 400;
            letter-spacing: 2px;
            color: #333;
        }

        .header-icons {
            display: flex;
            gap: 20px;
            align-items: center;
        }

        .header-icon {
            width: 24px;
            height: 24px;
            cursor: pointer;
        }

        /* メインビジュアル（土屋鞄のランドセル子供並び画像を模倣） */
        .main-visual {
            height: 100vh;
            background: url('https://cdn1.genspark.ai/user-upload-image/22_generated/19acffcf-9c2d-4637-b068-135a2b799609') center/cover;
            position: relative;
            margin-top: 70px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .main-visual::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0,0,0,0.3);
        }

        .main-visual-content {
            position: relative;
            z-index: 2;
            text-align: center;
            color: white;
        }

        .main-visual h1 {
            font-size: 2.5rem;
            font-weight: 300;
            margin-bottom: 20px;
            letter-spacing: 1px;
        }

        .main-visual p {
            font-size: 1.1rem;
            font-weight: 300;
            opacity: 0.9;
        }

        /* 3つのカテゴリー（土屋鞄のSTORE/CATALOG/CHECKを完全模倣） */
        .three-categories {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            height: 400px;
        }

        .category-item {
            position: relative;
            overflow: hidden;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .category-item:hover {
            transform: scale(1.02);
        }

        .category-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .category-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0,0,0,0.4);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
        }

        .category-title {
            font-size: 2rem;
            font-weight: 300;
            margin-bottom: 15px;
            letter-spacing: 3px;
        }

        .category-subtitle {
            font-size: 0.9rem;
            font-weight: 300;
            padding: 8px 20px;
            border: 1px solid white;
            border-radius: 20px;
            letter-spacing: 1px;
        }

        /* キャッチコピーセクション（土屋鞄の"6 Years, Filled with Memories"を模倣） */
        .catch-copy-section {
            padding: 120px 0;
            text-align: center;
            background: #f8f8f8;
        }

        .catch-copy {
            font-size: 3rem;
            font-weight: 300;
            color: #666;
            line-height: 1.4;
            margin-bottom: 40px;
            letter-spacing: 1px;
        }

        .catch-copy-sub {
            font-size: 1rem;
            color: #999;
            font-weight: 300;
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.8;
        }

        /* 特徴セクション（土屋鞄のFEATURES OF RANDOSERUを模倣） */
        .features-section {
            padding: 120px 20px;
            background: white;
        }

        .features-header {
            text-align: center;
            margin-bottom: 80px;
        }

        .features-title {
            font-size: 1.5rem;
            font-weight: 400;
            color: #333;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        .features-subtitle {
            font-size: 0.9rem;
            color: #999;
            font-weight: 300;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 40px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .feature-item {
            text-align: center;
        }

        .feature-image {
            width: 100%;
            height: 200px;
            background-size: cover;
            background-position: center;
            margin-bottom: 25px;
            border-radius: 8px;
        }

        .feature-title {
            font-size: 1rem;
            font-weight: 400;
            color: #333;
            margin-bottom: 15px;
        }

        .feature-description {
            font-size: 0.85rem;
            color: #666;
            line-height: 1.6;
            font-weight: 300;
        }

        /* サポートセクション（土屋鞄のALWAYS BY YOUR SIDEを模倣） */
        .support-section {
            padding: 120px 20px;
            background: #f8f8f8;
            text-align: center;
        }

        .support-header {
            margin-bottom: 80px;
        }

        .support-title {
            font-size: 1.5rem;
            font-weight: 400;
            color: #333;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        .support-subtitle {
            font-size: 0.9rem;
            color: #999;
            font-weight: 300;
        }

        .support-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 60px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .support-item {
            padding: 40px 20px;
        }

        .support-item h3 {
            font-size: 1.1rem;
            font-weight: 400;
            color: #333;
            margin-bottom: 15px;
        }

        .support-item p {
            font-size: 0.9rem;
            color: #666;
            line-height: 1.7;
            font-weight: 300;
        }

        /* 診断ツールセクション */
        .diagnosis-section {
            padding: 120px 20px;
            background: white;
            text-align: center;
        }

        .diagnosis-container {
            max-width: 800px;
            margin: 0 auto;
            background: #f8f8f8;
            padding: 60px 40px;
            border-radius: 4px;
        }

        .diagnosis-title {
            font-size: 1.5rem;
            font-weight: 400;
            color: #333;
            margin-bottom: 20px;
        }

        .diagnosis-form {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin: 40px 0;
        }

        .form-group label {
            display: block;
            font-size: 0.8rem;
            color: #666;
            margin-bottom: 8px;
            font-weight: 400;
        }

        .form-group input {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 14px;
            background: white;
        }

        .diagnosis-btn {
            background: #333;
            color: white;
            padding: 15px 40px;
            border: none;
            border-radius: 4px;
            font-size: 14px;
            cursor: pointer;
            margin-top: 20px;
            transition: background 0.3s ease;
        }

        .diagnosis-btn:hover {
            background: #555;
        }

        .diagnosis-result {
            margin-top: 30px;
            padding: 30px;
            background: white;
            border-radius: 4px;
            border-left: 4px solid #c4a882;
            display: none;
        }

        .diagnosis-result.show {
            display: block;
        }

        /* 特典セクション */
        .offer-section {
            padding: 120px 20px;
            background: #333;
            color: white;
            text-align: center;
        }

        .offer-badge {
            background: #c4a882;
            color: #333;
            padding: 8px 20px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 400;
            letter-spacing: 1px;
            margin-bottom: 30px;
            display: inline-block;
        }

        .offer-title {
            font-size: 2rem;
            font-weight: 300;
            margin-bottom: 20px;
        }

        .offer-description {
            font-size: 1rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto 40px;
            line-height: 1.8;
        }

        .offer-cta {
            background: white;
            color: #333;
            padding: 15px 40px;
            border: none;
            border-radius: 4px;
            font-size: 14px;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
        }

        .offer-cta:hover {
            background: #f0f0f0;
        }

        /* お問い合わせセクション */
        .contact-section {
            padding: 120px 20px;
            background: #f8f8f8;
            text-align: center;
        }

        .contact-container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 4px;
            overflow: hidden;
            box-shadow: 0 4px 20px rgba(0,0,0,0.1);
        }

        .contact-header {
            background: #666;
            color: white;
            padding: 40px;
        }

        .contact-header h3 {
            font-size: 1.3rem;
            font-weight: 400;
            margin-bottom: 10px;
        }

        .contact-header p {
            font-size: 0.9rem;
            opacity: 0.9;
        }

        .google-form-iframe {
            width: 100%;
            height: 985px;
            border: none;
        }

        /* フッター */
        .footer {
            background: #333;
            color: white;
            padding: 60px 20px 40px;
            text-align: center;
        }

        .footer-logo {
            font-size: 18px;
            font-weight: 400;
            letter-spacing: 2px;
            margin-bottom: 30px;
        }

        .footer-info {
            font-size: 0.9rem;
            line-height: 1.8;
            opacity: 0.8;
            margin-bottom: 20px;
        }

        .footer-phone {
            font-size: 1.2rem;
            color: #c4a882;
            margin-bottom: 30px;
        }

        .footer-copyright {
            font-size: 0.8rem;
            opacity: 0.6;
            border-top: 1px solid rgba(255,255,255,0.1);
            padding-top: 20px;
        }

        /* レスポンシブ */
        @media (max-width: 768px) {
            .three-categories {
                grid-template-columns: 1fr;
                height: auto;
            }

            .category-item {
                height: 300px;
            }

            .features-grid {
                grid-template-columns: 1fr;
                gap: 50px;
            }

            .support-grid {
                grid-template-columns: 1fr;
                gap: 40px;
            }

            .diagnosis-form {
                grid-template-columns: 1fr;
            }

            .catch-copy {
                font-size: 2rem;
            }

            .main-visual h1 {
                font-size: 2rem;
            }

            .features-section,
            .support-section,
            .diagnosis-section,
            .offer-section,
            .contact-section {
                padding: 80px 20px;
            }

            .google-form-iframe {
                height: 800px;
            }
        }
    </style>
</head>
<body>
    <!-- ヘッダー（土屋鞄完全模倣） -->
    <header class="header">
        <div class="header-content">
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="logo">BEST LINKS RENOVATION</div>
            <div class="header-icons">
                <svg class="header-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                    <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
                    <circle cx="12" cy="7" r="4"></circle>
                </svg>
                <svg class="header-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor">
                    <path d="M6 2L3 6v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V6l-3-4z"></path>
                    <line x1="3" y1="6" x2="21" y2="6"></line>
                    <path d="M16 10a4 4 0 0 1-8 0"></path>
                </svg>
            </div>
        </div>
    </header>

    <!-- メインビジュアル -->
    <section class="main-visual">
        <div class="main-visual-content">
            <h1>理想の住まいで、新しい暮らしを</h1>
            <p>15年以上前に住宅を購入されたご家族に向けた、住宅ローン借り換えリノベーション</p>
        </div>
    </section>

    <!-- 3つのカテゴリー（土屋鞄のSTORE/CATALOG/CHECKを完全模倣） -->
    <section class="three-categories">
        <div class="category-item">
            <img src="https://cdn1.genspark.ai/user-upload-image/22_generated/5c3216e1-33cd-411b-89a8-59fae3c5109d" alt="リノベーション">
            <div class="category-overlay">
                <div class="category-title">RENOVATION</div>
                <div class="category-subtitle">リノベーション事例はこちら</div>
            </div>
        </div>
        <div class="category-item">
            <img src="https://cdn1.genspark.ai/user-upload-image/22_generated/6babc2e6-2301-4b9b-8723-1447dec68a81" alt="診断">
            <div class="category-overlay">
                <div class="category-title">DIAGNOSIS</div>
                <div class="category-subtitle">借り換え診断をしてみる</div>
            </div>
        </div>
        <div class="category-item">
            <img src="https://cdn1.genspark.ai/user-upload-image/22_generated/19acffcf-9c2d-4637-b068-135a2b799609" alt="相談">
            <div class="category-overlay">
                <div class="category-title">CONSULTATION</div>
                <div class="category-subtitle">無料相談はこちら</div>
            </div>
        </div>
    </section>

    <!-- キャッチコピーセクション（土屋鞄の"6 Years, Filled with Memories"を模倣） -->
    <section class="catch-copy-section">
        <h2 class="catch-copy">Years,<br>Filled with<br>Dreams</h2>
        <p class="catch-copy-sub">
            こどもたちの願いを<br>
            のせながら、<br>
            安心してお家で過ごしてくれる<br>
            よう願っています。
        </p>
    </section>

    <!-- 特徴セクション（土屋鞄のFEATURES OF RANDOSERUを完全模倣） -->
    <section class="features-section">
        <div class="features-header">
            <h3 class="features-title">FEATURES OF RENOVATION</h3>
            <p class="features-subtitle">リノベーションの特徴</p>
        </div>
        <div class="features-grid">
            <div class="feature-item">
                <div class="feature-image" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/19acffcf-9c2d-4637-b068-135a2b799609');"></div>
                <h4 class="feature-title">美しく変わる空間</h4>
                <p class="feature-description">長年の実績と丁寧な施工で、ご家族の理想を実現いたします。</p>
            </div>
            <div class="feature-item">
                <div class="feature-image" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/5c3216e1-33cd-411b-89a8-59fae3c5109d');"></div>
                <h4 class="feature-title">最新の設備と技術</h4>
                <p class="feature-description">6年間使って頂ける強度や精度を実現いたします。</p>
            </div>
            <div class="feature-item">
                <div class="feature-image" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/6babc2e6-2301-4b9b-8723-1447dec68a81');"></div>
                <h4 class="feature-title">軽くて使いやすい設計</h4>
                <p class="feature-description">毎日の負担を少しでも和らげられるよう、ランドセルの軽量化を実現。</p>
            </div>
            <div class="feature-item">
                <div class="feature-image" style="background: linear-gradient(135deg, #e8e6e1 0%, #f7f6f4 100%); display: flex; align-items: center; justify-content: center; font-size: 3rem; color: #c4a882;">📐</div>
                <h4 class="feature-title">安心の収納力</h4>
                <p class="feature-description">教科書はもちろん、A4ファイルもしっかり収納。安心の収納力です。</p>
            </div>
        </div>
    </section>

    <!-- サポートセクション（土屋鞄のALWAYS BY YOUR SIDEを完全模倣） -->
    <section class="support-section">
        <div class="support-header">
            <h3 class="support-title">ALWAYS BY YOUR SIDE</h3>
            <p class="support-subtitle">永く寄り添う</p>
        </div>
        <div class="support-grid">
            <div class="support-item">
                <h3>6年間無料修理保証</h3>
                <p>元気いっぱいのお子さまが安心してお使いいただけるよう。</p>
            </div>
            <div class="support-item">
                <h3>ランドセルリメイク</h3>
                <p>卒業時には思い出と共に形を変えてお手元に。</p>
            </div>
            <div class="support-item">
                <h3>全国後楽サービス</h3>
                <p>大切に愛したい、突然のことにも迅速に対応いたします。</p>
            </div>
        </div>
    </section>

    <!-- 診断ツールセクション -->
    <section class="diagnosis-section">
        <div class="diagnosis-container">
            <h3 class="diagnosis-title">30秒無料診断</h3>
            <p>現在の住宅ローン情報から、借り換えメリットを診断いたします。</p>
            
            <div class="diagnosis-form">
                <div class="form-group">
                    <label>現在の借入金利（%）</label>
                    <input type="number" id="currentRate" step="0.1" placeholder="1.5">
                </div>
                <div class="form-group">
                    <label>ローン残高（万円）</label>
                    <input type="number" id="loanBalance" placeholder="2500">
                </div>
                <div class="form-group">
                    <label>借入年数（年）</label>
                    <input type="number" id="loanYears" placeholder="15">
                </div>
            </div>
            
            <button class="diagnosis-btn" onclick="calculateRenovationBudget()">診断する</button>
            
            <div class="diagnosis-result" id="renovationResult">
                <h4 style="color: #c4a882; margin-bottom: 15px;">診断結果</h4>
                <p style="font-size: 1.2rem; font-weight: bold; margin-bottom: 10px;" id="renovationBudget">リノベーション予算目安: 約500万円</p>
                <p style="font-size: 0.9rem; color: #666;">※0.7%の金利で借り換えした場合の試算結果です</p>
            </div>
        </div>
    </section>

    <!-- 特典セクション -->
    <section class="offer-section">
        <div class="offer-badge">6月限定特典</div>
        <h3 class="offer-title">10万円までの家具を1つプレゼント</h3>
        <p class="offer-description">
            6月中にご契約いただいた方限定で、新しい住まいにぴったりの家具をプレゼントいたします。<br>
            理想のリノベーションを、さらに魅力的に仕上げませんか？
        </p>
        <a href="#contact" class="offer-cta">今すぐ相談する</a>
    </section>

    <!-- お問い合わせセクション -->
    <section class="contact-section" id="contact">
        <div class="contact-container">
            <div class="contact-header">
                <h3>まずはお気軽にご相談ください</h3>
                <p>住宅ローン借り換えとリノベーションについて、専門スタッフがサポートいたします。</p>
            </div>
            <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSe6DP0u7hJmlwFP8kdO9W0FaMs2tfdSpPlAnuvqpRaU6KFdAg/viewform?embedded=true" class="google-form-iframe" frameborder="0" marginheight="0" marginwidth="0">読み込んでいます…</iframe>
        </div>
    </section>

    <!-- フッター -->
    <footer class="footer">
        <div class="footer-logo">BEST LINKS</div>
        <div class="footer-info">
            〒533-0033<br>
            大阪府大阪市東淀川区東中島2-26-10 ユウアイビル3F<br>
            営業時間：9:30〜17:00（土日祝除く）
        </div>
        <div class="footer-phone">06-6657-5092</div>
        <div class="footer-copyright">
            © 2024 BEST LINKS CO., LTD. All rights reserved.
        </div>
    </footer>

    <script>
        // 診断ツール機能
        function calculateRenovationBudget() {
            const currentRate = parseFloat(document.getElementById('currentRate').value) || 0;
            const loanBalance = parseFloat(document.getElementById('loanBalance').value) || 0;
            const loanYears = parseFloat(document.getElementById('loanYears').value) || 0;

            if (currentRate === 0 || loanBalance === 0 || loanYears === 0) {
                alert('すべての項目を入力してください');
                return;
            }

            // 簡易計算（0.7%削減想定）
            const newRate = Math.max(0.5, currentRate - 0.7);
            const monthlyReduction = loanBalance * (currentRate - newRate) / 100 / 12;
            const totalReduction = monthlyReduction * (35 - loanYears) * 12;
            const renovationBudget = Math.min(totalReduction * 0.8, 1000); // 上限1000万

            document.getElementById('renovationBudget').textContent = 
                `リノベーション予算目安: 約${Math.round(renovationBudget)}万円`;
            document.getElementById('renovationResult').classList.add('show');
        }

        // スムーススクロール
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });

        // カテゴリーアイテムのクリックイベント
        document.querySelectorAll('.category-item').forEach((item, index) => {
            item.addEventListener('click', function() {
                if (index === 0) {
                    document.querySelector('.features-section').scrollIntoView({ behavior: 'smooth' });
                } else if (index === 1) {
                    document.querySelector('.diagnosis-section').scrollIntoView({ behavior: 'smooth' });
                } else if (index === 2) {
                    document.querySelector('.contact-section').scrollIntoView({ behavior: 'smooth' });
                }
            });
        });
    </script>
</body>
</html>
