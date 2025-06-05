<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>住宅ローン借り換えリノベーション | 株式会社ベストリンクス</title>
    <meta name="description" content="15年以上前に住宅を購入されたご家族へ。住宅ローン借り換えで実質無料リノベーション。毎月の支払いを変えずに理想の住まいを実現。">
    <style>
        :root {
            /* 土屋鞄風グレイッシュカラーパレット */
            --charcoal: #2a2a2a;
            --warm-gray: #f7f6f4;
            --light-gray: #e8e6e1;
            --medium-gray: #a8a8a8;
            --dark-gray: #5a5a5a;
            --accent-warm: #c4a882;
            --accent-gold: #d4af37;
            --white: #ffffff;
            --text-primary: #2a2a2a;
            --text-secondary: #666666;
            --border-color: rgba(42,42,42,0.1);
            --shadow-soft: rgba(0,0,0,0.06);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
            line-height: 1.7;
            color: var(--text-primary);
            -webkit-text-size-adjust: 100%;
            -webkit-font-smoothing: antialiased;
            background-color: var(--warm-gray);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 40px;
        }

        /* ヘッダー（土屋鞄風） */
        .header {
            background: rgba(247,246,244,0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border-color);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            transition: all 0.3s ease;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 25px 40px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 18px;
            font-weight: 400;
            color: var(--text-primary);
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .header-nav {
            display: flex;
            gap: 40px;
            align-items: center;
        }

        .nav-link {
            color: var(--text-secondary);
            text-decoration: none;
            font-size: 14px;
            font-weight: 300;
            letter-spacing: 1px;
            transition: color 0.3s ease;
        }

        .nav-link:hover {
            color: var(--text-primary);
        }

        .header-cta {
            background: var(--charcoal);
            color: white;
            padding: 12px 30px;
            border: none;
            font-weight: 300;
            text-decoration: none;
            font-size: 13px;
            letter-spacing: 1px;
            text-transform: uppercase;
            transition: all 0.3s ease;
        }

        .header-cta:hover {
            background: var(--dark-gray);
        }

        /* メインビジュアル（土屋鞄のように子供たちが並んでいるイメージ） */
        .hero {
            background: url('https://cdn1.genspark.ai/user-upload-image/22_generated/19acffcf-9c2d-4637-b068-135a2b799609');
            background-size: cover;
            background-position: center;
            height: 70vh;
            position: relative;
            margin-top: 80px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(42,42,42,0.4);
        }

        .hero-content {
            position: relative;
            z-index: 2;
            text-align: center;
            color: white;
            max-width: 600px;
        }

        .hero-badge {
            background: var(--accent-gold);
            color: var(--charcoal);
            padding: 8px 20px;
            font-size: 11px;
            font-weight: 400;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 30px;
            display: inline-block;
        }

        .hero h1 {
            font-size: 2.8rem;
            font-weight: 300;
            letter-spacing: 2px;
            line-height: 1.3;
            margin-bottom: 25px;
        }

        .hero-subtitle {
            font-size: 1.1rem;
            font-weight: 300;
            opacity: 0.9;
            line-height: 1.6;
            margin-bottom: 40px;
        }

        /* 3つのカテゴリーカード（土屋鞄のSTORE, CATALOG, CHECKのように） */
        .category-section {
            padding: 0;
            margin-top: -100px;
            position: relative;
            z-index: 3;
        }

        .category-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 0;
        }

        .category-card {
            background-size: cover;
            background-position: center;
            height: 300px;
            position: relative;
            display: flex;
            align-items: end;
            color: white;
            text-decoration: none;
            transition: transform 0.3s ease;
        }

        .category-card:hover {
            transform: scale(1.02);
        }

        .category-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(transparent 50%, rgba(0,0,0,0.7));
        }

        .category-content {
            position: relative;
            z-index: 2;
            padding: 40px;
            width: 100%;
        }

        .category-title {
            font-size: 1.5rem;
            font-weight: 300;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 10px;
        }

        .category-desc {
            font-size: 0.9rem;
            opacity: 0.9;
            font-weight: 300;
        }

        /* メインコンテンツエリア */
        .main-content {
            background: var(--white);
            padding: 120px 0;
        }

        .content-header {
            text-align: center;
            margin-bottom: 100px;
        }

        .content-title {
            font-size: 2.5rem;
            font-weight: 300;
            color: var(--text-primary);
            letter-spacing: 1px;
            line-height: 1.4;
            margin-bottom: 30px;
        }

        .content-subtitle {
            font-size: 1rem;
            color: var(--text-secondary);
            line-height: 1.8;
            max-width: 600px;
            margin: 0 auto;
            font-weight: 300;
        }

        /* 特徴セクション（土屋鞄のランドセルの特徴のように） */
        .features-section {
            background: var(--warm-gray);
            padding: 120px 0;
        }

        .features-header {
            text-align: center;
            margin-bottom: 80px;
        }

        .features-title {
            font-size: 1.8rem;
            font-weight: 300;
            color: var(--text-primary);
            letter-spacing: 1px;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .features-subtitle {
            font-size: 0.9rem;
            color: var(--text-secondary);
            font-weight: 300;
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 40px;
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
            border: 1px solid var(--border-color);
        }

        .feature-title {
            font-size: 1rem;
            font-weight: 400;
            color: var(--text-primary);
            margin-bottom: 15px;
            letter-spacing: 0.5px;
        }

        .feature-desc {
            font-size: 0.85rem;
            color: var(--text-secondary);
            line-height: 1.6;
            font-weight: 300;
        }

        /* サポートセクション（土屋鞄のALWAYS BY YOUR SIDEのように） */
        .support-section {
            background: var(--white);
            padding: 120px 0;
        }

        .support-header {
            text-align: center;
            margin-bottom: 80px;
        }

        .support-title {
            font-size: 1.8rem;
            font-weight: 300;
            color: var(--text-primary);
            letter-spacing: 1px;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .support-subtitle {
            font-size: 0.9rem;
            color: var(--text-secondary);
            font-weight: 300;
        }

        .support-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 60px;
        }

        .support-item {
            text-align: center;
        }

        .support-icon {
            width: 60px;
            height: 60px;
            background: var(--light-gray);
            border-radius: 50%;
            margin: 0 auto 25px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            color: var(--accent-warm);
        }

        .support-item-title {
            font-size: 1.1rem;
            font-weight: 400;
            color: var(--text-primary);
            margin-bottom: 15px;
            letter-spacing: 0.5px;
        }

        .support-item-desc {
            font-size: 0.9rem;
            color: var(--text-secondary);
            line-height: 1.7;
            font-weight: 300;
        }

        /* 診断ツールセクション */
        .diagnosis-section {
            background: var(--warm-gray);
            padding: 120px 0;
        }

        .diagnosis-container {
            max-width: 800px;
            margin: 0 auto;
            background: var(--white);
            padding: 60px;
            border: 1px solid var(--border-color);
        }

        .diagnosis-header {
            text-align: center;
            margin-bottom: 50px;
        }

        .diagnosis-title {
            font-size: 1.8rem;
            font-weight: 300;
            color: var(--text-primary);
            letter-spacing: 1px;
            margin-bottom: 20px;
        }

        .diagnosis-desc {
            font-size: 0.9rem;
            color: var(--text-secondary);
            font-weight: 300;
        }

        .diagnosis-form {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            margin-bottom: 40px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        .form-group label {
            font-size: 0.8rem;
            color: var(--text-primary);
            margin-bottom: 8px;
            font-weight: 400;
            letter-spacing: 0.5px;
            text-transform: uppercase;
        }

        .form-group input {
            padding: 15px;
            border: 1px solid var(--border-color);
            font-size: 14px;
            background: var(--warm-gray);
            font-weight: 300;
            transition: border-color 0.3s ease;
        }

        .form-group input:focus {
            outline: none;
            border-color: var(--charcoal);
        }

        .diagnosis-btn {
            background: var(--charcoal);
            color: white;
            padding: 18px 40px;
            border: none;
            font-size: 13px;
            font-weight: 400;
            letter-spacing: 1px;
            text-transform: uppercase;
            cursor: pointer;
            transition: background 0.3s ease;
            width: 100%;
        }

        .diagnosis-btn:hover {
            background: var(--dark-gray);
        }

        .diagnosis-result {
            margin-top: 40px;
            padding: 40px;
            background: var(--warm-gray);
            border-left: 3px solid var(--accent-warm);
            display: none;
        }

        .diagnosis-result.show {
            display: block;
        }

        .result-highlight {
            font-size: 1.5rem;
            font-weight: 300;
            color: var(--text-primary);
            text-align: center;
            margin-bottom: 20px;
            letter-spacing: 1px;
        }

        /* 特典セクション */
        .offer-section {
            background: var(--charcoal);
            color: white;
            padding: 120px 0;
            text-align: center;
        }

        .offer-badge {
            background: var(--accent-gold);
            color: var(--charcoal);
            padding: 10px 30px;
            font-size: 11px;
            font-weight: 400;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 40px;
            display: inline-block;
        }

        .offer-title {
            font-size: 2rem;
            font-weight: 300;
            margin-bottom: 30px;
            letter-spacing: 1px;
        }

        .offer-desc {
            font-size: 1rem;
            opacity: 0.9;
            line-height: 1.8;
            font-weight: 300;
            max-width: 600px;
            margin: 0 auto 50px;
        }

        .offer-cta {
            background: var(--white);
            color: var(--charcoal);
            padding: 18px 50px;
            border: none;
            font-size: 13px;
            font-weight: 400;
            letter-spacing: 1px;
            text-transform: uppercase;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
        }

        .offer-cta:hover {
            background: var(--light-gray);
        }

        /* お問い合わせセクション */
        .contact-section {
            background: var(--white);
            padding: 120px 0;
        }

        .contact-container {
            max-width: 800px;
            margin: 0 auto;
            border: 1px solid var(--border-color);
            overflow: hidden;
        }

        .contact-header {
            background: var(--dark-gray);
            color: white;
            padding: 50px;
            text-align: center;
        }

        .contact-title {
            font-size: 1.5rem;
            font-weight: 300;
            margin-bottom: 15px;
            letter-spacing: 1px;
        }

        .contact-desc {
            font-size: 0.9rem;
            opacity: 0.9;
            font-weight: 300;
        }

        .google-form-wrapper {
            background: var(--white);
        }

        .google-form-iframe {
            width: 100%;
            border: none;
            min-height: 985px;
            background: white;
        }

        /* フッター */
        .footer {
            background: var(--charcoal);
            color: white;
            padding: 80px 0 50px;
        }

        .footer-content {
            text-align: center;
        }

        .footer-logo {
            font-size: 18px;
            font-weight: 400;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 30px;
            color: var(--accent-warm);
        }

        .footer-info {
            font-size: 0.85rem;
            line-height: 1.8;
            opacity: 0.8;
            font-weight: 300;
            margin-bottom: 20px;
        }

        .footer-phone {
            font-size: 1.2rem;
            color: var(--accent-gold);
            font-weight: 300;
            letter-spacing: 1px;
            margin-bottom: 30px;
        }

        .footer-copyright {
            font-size: 0.75rem;
            opacity: 0.6;
            font-weight: 300;
            border-top: 1px solid rgba(255,255,255,0.1);
            padding-top: 30px;
            margin-top: 30px;
        }

        /* レスポンシブ対応 */
        @media (max-width: 1024px) {
            .container {
                padding: 0 30px;
            }

            .header-content {
                padding: 20px 30px;
            }

            .category-grid {
                grid-template-columns: 1fr;
            }

            .features-grid {
                grid-template-columns: repeat(2, 1fr);
            }

            .diagnosis-form {
                grid-template-columns: 1fr;
                gap: 20px;
            }
        }

        @media (max-width: 768px) {
            .container {
                padding: 0 20px;
            }

            .header-content {
                flex-direction: column;
                gap: 15px;
                padding: 15px 20px;
            }

            .header-nav {
                display: none;
            }

            .logo {
                font-size: 16px;
            }

            .hero {
                height: 60vh;
                margin-top: 90px;
            }

            .hero h1 {
                font-size: 2.2rem;
            }

            .hero-subtitle {
                font-size: 1rem;
            }

            .category-grid {
                grid-template-columns: 1fr;
                margin-top: -50px;
            }

            .category-card {
                height: 250px;
            }

            .main-content,
            .features-section,
            .support-section,
            .diagnosis-section,
            .offer-section,
            .contact-section {
                padding: 80px 0;
            }

            .content-title {
                font-size: 2rem;
            }

            .features-grid {
                grid-template-columns: 1fr;
                gap: 50px;
            }

            .support-grid {
                grid-template-columns: 1fr;
                gap: 50px;
            }

            .diagnosis-container {
                padding: 40px 30px;
                margin: 0 20px;
            }

            .contact-header {
                padding: 40px 30px;
            }

            .google-form-iframe {
                min-height: 800px;
            }

            .footer {
                padding: 60px 0 40px;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 15px;
            }

            .hero h1 {
                font-size: 1.8rem;
            }

            .category-card {
                height: 200px;
            }

            .diagnosis-container {
                padding: 30px 20px;
                margin: 0 15px;
            }

            .google-form-iframe {
                min-height: 750px;
            }
        }

        /* アニメーション */
        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s ease;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <!-- ヘッダー -->
    <header class="header">
        <div class="header-content">
            <div class="logo">BEST LINKS</div>
            <nav class="header-nav">
                <a href="#features" class="nav-link">サービス</a>
                <a href="#diagnosis" class="nav-link">診断</a>
                <a href="#support" class="nav-link">サポート</a>
                <a href="#contact" class="header-cta">相談</a>
            </nav>
        </div>
    </header>

    <!-- メインビジュアル -->
    <section class="hero">
        <div class="hero-content">
            <div class="hero-badge">Limited Offer</div>
            <h1>実質無料で<br>リノベができる</h1>
            <p class="hero-subtitle">15年以上前に住宅を購入されたご家族に向けた、<br>住宅ローン借り換えによるリノベーション提案</p>
        </div>
    </section>

    <!-- カテゴリーセクション -->
    <section class="category-section">
        <div class="container">
            <div class="category-grid">
                <a href="#diagnosis" class="category-card" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/5c3216e1-33cd-411b-89a8-59fae3c5109d');">
                    <div class="category-content">
                        <div class="category-title">DIAGNOSIS</div>
                        <div class="category-desc">30秒で分かる借り換えメリット診断</div>
                    </div>
                </a>
                <a href="#features" class="category-card" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/19acffcf-9c2d-4637-b068-135a2b799609');">
                    <div class="category-content">
                        <div class="category-title">RENOVATION</div>
                        <div class="category-desc">理想の住まいへのリノベーション</div>
                    </div>
                </a>
                <a href="#contact" class="category-card" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/6babc2e6-2301-4b9b-8723-1447dec68a81');">
                    <div class="category-content">
                        <div class="category-title">CONSULTATION</div>
                        <div class="category-desc">専門家による無料相談</div>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- メインコンテンツ -->
    <section class="main-content">
        <div class="container">
            <div class="content-header fade-in">
                <h2 class="content-title">毎月の支払いを変えずに、<br>理想の住まいへ</h2>
                <p class="content-subtitle">住宅ローンの借り換えを活用することで、リノベーション資金を確保し、<br>月々の負担を増やすことなく理想の住まいを実現できる可能性があります。</p>
            </div>
        </div>
    </section>

    <!-- 特徴セクション -->
    <section class="features-section" id="features">
        <div class="container">
            <div class="features-header fade-in">
                <h3 class="features-title">Features of Renovation</h3>
                <p class="features-subtitle">リノベーションの特徴</p>
            </div>
            <div class="features-grid">
                <div class="feature-item fade-in">
                    <div class="feature-image" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/19acffcf-9c2d-4637-b068-135a2b799609');"></div>
                    <h4 class="feature-title">開放的な空間設計</h4>
                    <p class="feature-desc">間取りを自由に変更し、家族が自然に集まる開放的なリビング空間を創造します。</p>
                </div>
                <div class="feature-item fade-in">
                    <div class="feature-image" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/5c3216e1-33cd-411b-89a8-59fae3c5109d');"></div>
                    <h4 class="feature-title">最新設備の導入</h4>
                    <p class="feature-desc">使いやすさを追求したシステムキッチンや最新の住宅設備で快適な暮らしを実現します。</p>
                </div>
                <div class="feature-item fade-in">
                    <div class="feature-image" style="background-image: url('https://cdn1.genspark.ai/user-upload-image/22_generated/6babc2e6-2301-4b9b-8723-1447dec68a81');"></div>
                    <h4 class="feature-title">快適な水回り</h4>
                    <p class="feature-desc">清潔で機能的なバスルームと洗面所で、毎日の生活がより快適になります。</p>
                </div>
                <div class="feature-item fade-in">
                    <div class="feature-image" style="background: linear-gradient(135deg, #e8e6e1 0%, #f7f6f4 100%); display: flex; align-items: center; justify-content: center; font-size: 3rem; color: var(--accent-warm);">💡</div>
                    <h4 class="feature-title">省エネ性能向上</h4>
                    <p class="feature-desc">断熱性能の向上により、一年中快適な住環境と光熱費の削減を実現します。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- サポートセクション -->
    <section class="support-section" id="support">
        <div class="container">
            <div class="support-header fade-in">
                <h3 class="support-title">Always by your side</h3>
                <p class="support-subtitle">あなたのそばで寄り添う</p>
            </div>
            <div class="support-grid">
                <div class="support-item fade-in">
                    <div class="support-icon">💰</div>
                    <h4 class="support-item-title">住宅ローンのプロフェッショナル</h4>
                    <p class="support-item-desc">借り換えの豊富な知識と実績で、お客様に最適なプランをご提案いたします。</p>
                </div>
                <div class="support-item fade-in">
                    <div class="support-icon">🎨</div>
                    <h4 class="support-item-title">デザイン性の高い提案</h4>
                    <p class="support-item-desc">機能性とデザイン性を兼ね備えた、理想の住まいづくりをサポートします。</p>
                </div>
                <div class="support-item fade-in">
                    <div class="support-icon">🤝</div>
                    <h4 class="support-item-title">安心の一貫体制</h4>
                    <p class="support-item-desc">ご相談から施工完了まで、一人の担当者が責任を持ってサポートいたします。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 診断ツールセクション -->
    <section class="diagnosis-section" id="diagnosis">
        <div class="container">
            <div class="diagnosis-container fade-in">
                <div class="diagnosis-header">
                    <h3 class="diagnosis-title">30秒無料診断</h3>
                    <p class="diagnosis-desc">現在の住宅ローン情報を入力いただくと、借り換えによるリノベーション予算の目安をご確認いただけます。</p>
                </div>
                <div class="diagnosis-form">
                    <div class="form-group">
                        <label>現在の借入金利（%）</label>
                        <input type="number" id="currentRate" step="0.1" placeholder="1.5">
                    </div>
                    <div class="form-group">
