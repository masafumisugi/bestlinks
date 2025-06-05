<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>住宅ローン借り換えでリノベーション資金を調達 | 株式会社ベストリンクス</title>
    <meta name="description" content="住宅ローンの借り換えでリノベーション資金を賢く調達。金利差を活用して夢の住まいを実現しませんか？簡易診断ツールで今すぐメリットをチェック！">
    <style>
        :root {
            --vh: 1vh;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* ヘッダー */
        .header {
            background: #fff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            transition: transform 0.3s ease;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #2c5aa0;
        }

        .header-cta {
            background: #ff6b35;
            color: white !important;
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            font-weight: bold;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .header-cta:hover {
            background: #e55a2b;
            transform: translateY(-2px);
            color: white !important;
        }

        /* ヒーローセクション */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 120px 0 80px;
            text-align: center;
            margin-top: 70px;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .hero .subtitle {
            font-size: 1.5rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .hero .highlight {
            background: #ff6b35;
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: bold;
        }

        /* 診断ツールセクション */
        .diagnosis {
            background: white;
            padding: 80px 0;
            border-top: 5px solid #ff6b35;
        }

        .diagnosis h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 50px;
            color: #2c5aa0;
        }

        .diagnosis-form {
            background: #f8f9fa;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 800px;
            margin: 0 auto;
        }

        .form-group {
            margin-bottom: 25px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
            color: #333;
        }

        .form-group input, .form-group select {
            width: 100%;
            padding: 15px;
            border: 2px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s ease;
        }

        .form-group input:focus, .form-group select:focus {
            outline: none;
            border-color: #667eea;
        }

        .diagnosis-btn {
            background: linear-gradient(45deg, #ff6b35, #f7931e);
            color: white;
            padding: 18px 40px;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            transition: all 0.3s ease;
        }

        .diagnosis-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(255, 107, 53, 0.3);
        }

        .result {
            margin-top: 30px;
            padding: 30px;
            background: white;
            border-radius: 10px;
            border-left: 5px solid #28a745;
            display: none;
        }

        .result.show {
            display: block;
            animation: slideDown 0.5s ease;
        }

        @keyframes slideDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .result h3 {
            color: #28a745;
            margin-bottom: 20px;
            font-size: 1.5rem;
        }

        .result-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 15px;
            padding: 10px 0;
            border-bottom: 1px solid #eee;
        }

        .result-value {
            font-weight: bold;
            color: #ff6b35;
        }

        /* メリットセクション */
        .benefits {
            background: #f8f9fa;
            padding: 80px 0;
        }

        .benefits h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 60px;
            color: #2c5aa0;
        }

        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .benefit-card {
            background: white;
            padding: 40px 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .benefit-card:hover {
            transform: translateY(-10px);
        }

        .benefit-icon {
            font-size: 4rem;
            margin-bottom: 20px;
        }

        .benefit-card h3 {
            color: #2c5aa0;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }

        /* 事例セクション */
        .cases {
            padding: 80px 0;
            background: white;
        }

        .cases h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 60px;
            color: #2c5aa0;
        }

        .case-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
        }

        .case-card {
            background: #f8f9fa;
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid #ff6b35;
        }

        .case-card h3 {
            color: #2c5aa0;
            margin-bottom: 15px;
        }

        .case-details {
            margin: 20px 0;
        }

        .case-detail {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
        }

        .case-result {
            background: #28a745;
            color: white;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            font-weight: bold;
            margin-top: 20px;
        }

        /* サービス紹介セクション */
        .services {
            background: #f8f9fa;
            padding: 80px 0;
        }

        .services h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 60px;
            color: #2c5aa0;
        }

        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .service-card {
            background: white;
            padding: 30px 20px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card h3 {
            color: #2c5aa0;
            margin-bottom: 15px;
        }

        /* 会社紹介セクション */
        .company {
            padding: 80px 0;
            background: white;
        }

        .company h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 60px;
            color: #2c5aa0;
        }

        .company-content {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 40px;
            align-items: center;
        }

        .company-info h3 {
            color: #2c5aa0;
            margin-bottom: 20px;
            font-size: 1.5rem;
        }

        .company-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .stat-card {
            text-align: center;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 10px;
        }

        .stat-number {
            font-size: 2rem;
            font-weight: bold;
            color: #ff6b35;
        }

        .stat-label {
            color: #666;
            font-size: 0.9rem;
        }

        /* お問い合わせセクション */
        .contact {
            background: linear-gradient(135deg, #2c5aa0 0%, #667eea 100%);
            color: white;
            padding: 80px 0;
        }

        .contact h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 60px;
        }

        .google-form-btn {
            display: inline-block;
            background: linear-gradient(45deg, #ff6b35, #f7931e);
            color: white !important;
            padding: 20px 40px;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(255, 107, 53, 0.3);
            border: none;
            cursor: pointer;
        }

        .google-form-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(255, 107, 53, 0.4);
            color: white !important;
        }

        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 60px;
        }

        .contact-method {
            background: rgba(255,255,255,0.1);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            backdrop-filter: blur(10px);
        }

        .contact-icon {
            font-size: 3rem;
            margin-bottom: 15px;
        }

        .contact-method h3 {
            margin-bottom: 15px;
            font-size: 1.3rem;
        }

        .phone-number {
            font-size: 1.5rem;
            font-weight: bold;
            color: #ff6b35;
            margin: 10px 0;
        }

        /* フッター */
        .footer {
            background: #333;
            color: white;
            padding: 40px 0;
            text-align: center;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }

        .footer h3 {
            margin-bottom: 15px;
            color: #ff6b35;
        }

        .footer-links a {
            color: #ccc;
            text-decoration: none;
            display: block;
            margin-bottom: 8px;
            transition: color 0.3s ease;
        }

        .footer-links a:hover {
            color: #ff6b35;
        }

        .fade-in {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.6s ease;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* ===== スマートフォン対応（完全版） ===== */

        /* タブレット対応 */
        @media (max-width: 1024px) {
            .container {
                padding: 0 15px;
            }
            
            .hero h1 {
                font-size: 3rem;
            }
            
            .diagnosis-form {
                padding: 35px 25px;
            }
        }

        /* スマートフォン対応 */
        @media (max-width: 768px) {
            /* ヘッダー */
            .header-content {
                flex-direction: column;
                gap: 10px;
                padding: 10px 15px;
            }
            
            .logo {
                font-size: 20px;
            }
            
            .header-cta {
                padding: 10px 20px;
                font-size: 14px;
            }
            
            /* ヒーローセクション */
            .hero {
                padding: 100px 0 60px;
                margin-top: 80px;
            }
            
            .hero h1 {
                font-size: 2.2rem;
                line-height: 1.3;
                margin-bottom: 15px;
            }
            
            .hero .subtitle {
                font-size: 1.1rem;
                margin-bottom: 20px;
            }
            
            .hero .highlight {
                padding: 3px 10px;
                display: inline-block;
                margin: 5px 0;
            }
            
            /* 診断ツール */
            .diagnosis {
                padding: 60px 0;
            }
            
            .diagnosis h2 {
                font-size: 2rem;
                margin-bottom: 30px;
                line-height: 1.3;
            }
            
            .diagnosis-form {
                padding: 25px 20px;
                margin: 0 10px;
            }
            
            .form-group {
                margin-bottom: 20px;
            }
            
            .form-group label {
                font-size: 14px;
                margin-bottom: 6px;
            }
            
            .form-group input {
                padding: 12px;
                font-size: 16px;
                -webkit-appearance: none;
                border-radius: 8px;
            }
            
            .diagnosis-btn {
                padding: 15px 30px;
                font-size: 16px;
                -webkit-appearance: none;
            }
            
            .result {
                padding: 20px;
                margin-top: 20px;
            }
            
            .result h3 {
                font-size: 1.3rem;
                margin-bottom: 15px;
            }
            
            .result-item {
                flex-direction: column;
                text-align: center;
                margin-bottom: 12px;
                padding: 8px 0;
            }
            
            .result-value {
                font-size: 1.1rem;
                margin-top: 5px;
            }
            
            /* セクション共通 */
            .benefits, .cases, .services, .company, .contact {
                padding: 60px 0;
            }
            
            .benefits h2, .cases h2, .services h2, .company h2, .contact h2 {
                font-size: 2rem;
                margin-bottom: 40px;
                line-height: 1.3;
            }
            
            /* メリットセクション */
            .benefits-grid {
                grid-template-columns: 1fr;
                gap: 25px;
            }
            
            .benefit-card {
                padding: 30px 20px;
            }
            
            .benefit-icon {
                font-size: 3rem;
            }
            
            .benefit-card h3 {
                font-size: 1.3rem;
                margin-bottom: 12px;
            }
            
            .benefit-card p {
                font-size: 14px;
                line-height: 1.5;
            }
            
            /* 事例セクション */
            .case-grid {
                grid-template-columns: 1fr;
                gap: 25px;
            }
            
            .case-card {
                padding: 20px;
                margin: 0 10px;
            }
            
            .case-card h3 {
                font-size: 1.2rem;
                line-height: 1.4;
            }
            
            .case-detail {
                font-size: 14px;
                margin-bottom: 8px;
            }
            
            .case-result {
                padding: 12px;
                font-size: 14px;
                margin-top: 15px;
            }
            
            /* サービスセクション */
            .service-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }
            
            .service-card {
                padding: 25px 15px;
            }
            
            .service-card h3 {
                font-size: 1.2rem;
            }
            
            .service-card p {
                font-size: 14px;
            }
            
            /* 会社紹介セクション */
            .company-content {
                grid-template-columns: 1fr;
                gap: 30px;
            }
            
            .company-info h3 {
                font-size: 1.3rem;
                line-height: 1.4;
            }
            
            .company-info p {
                font-size: 14px;
                line-height: 1.6;
            }
            
            .company-stats {
                grid-template-columns: repeat(3, 1fr);
                gap: 15px;
            }
            
            .stat-card {
                padding: 15px 10px;
            }
            
            .stat-number {
                font-size: 1.5rem;
            }
            
            .stat-label {
                font-size: 0.8rem;
            }
            
            /* お問い合わせセクション */
            .google-form-btn {
                padding: 15px 30px;
                font-size: 16px;
                display: block;
                width: 90%;
                margin: 0 auto;
                text-align: center;
                -webkit-appearance: none;
            }
            
            .contact-info {
                grid-template-columns: 1fr;
                gap: 20px;
                margin-top: 40px;
            }
            
            .contact-method {
                padding: 20px 15px;
            }
            
            .contact-icon {
                font-size: 2.5rem;
            }
            
            .contact-method h3 {
                font-size: 1.2rem;
            }
            
            .contact-method p {
                font-size: 14px;
            }
            
            .phone-number {
                font-size: 1.3rem !important;
            }
            
            /* フッター */
            .footer {
                padding: 30px 0;
            }
            
            .footer-content {
                grid-template-columns: 1fr;
                gap: 20px;
                text-align: left;
            }
            
            .footer h3 {
                font-size: 1.1rem;
            }
            
            .footer p, .footer-links a {
                font-size: 14px;
            }
        }

        /* 小さなスマートフォン対応 */
        @media (max-width: 480px) {
            .container {
                padding: 0 10px;
            }
            
            .hero h1 {
                font-size: 1.8rem;
                line-height: 1.2;
            }
            
            .hero .subtitle {
                font-size: 1rem;
            }
            
            .diagnosis-form {
                padding: 20px 15px;
                margin: 0 5px;
            }
            
            .diagnosis h2 {
                font-size: 1.7rem;
            }
            
            .form-group input {
                padding: 10px;
            }
            
            .diagnosis-btn {
                padding: 12px 25px;
                font-size: 15px;
            }
            
            .benefits h2, .cases h2, .services h2, .company h2, .contact h2 {
                font-size: 1.7rem;
            }
            
            .benefit-card, .case-card, .service-card {
                margin: 0 5px;
            }
            
            .google-form-btn {
                width: 95%;
                padding: 12px 20px;
                font-size: 15px;
            }
            
            .company-stats {
                grid-template-columns: 1fr;
                gap: 10px;
            }
        }

        /* 横向きスマートフォン対応 */
        @media (max-width: 768px) and (orientation: landscape) {
            .hero {
                padding: 80px 0 40px;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .diagnosis, .benefits, .cases, .services, .company, .contact {
                padding: 40px 0;
            }
            
            .benefits-grid, .service-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .case-grid {
                grid-template-columns: 1fr;
            }
        }

        /* タッチデバイス用の改善 */
        @media (hover: none) {
            .benefit-card:hover,
            .service-card:hover {
                transform: none;
            }
            
            .google-form-btn:active,
            .header-cta:active,
            .diagnosis-btn:active {
                transform: scale(0.98);
            }
        }

        /* 高DPIディスプレイ対応 */
        @media (-webkit-min-device-pixel-ratio: 2), (min-resolution: 192dpi) {
            .hero {
                background-attachment: scroll;
            }
        }

        /* スクロール時のヘッダー動作改善 */
        @media (max-width: 768px) {
            .header.hidden {
                transform: translateY(-100%);
            }
            
            .fade-in {
                opacity: 1;
                transform: translateY(0);
            }
            
            .fade-in.visible {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .touch-device * {
            -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
        }
    </style>
</head>
<body>
    <!-- ヘッダー -->
    <header class="header">
        <div class="header-content">
            <div class="logo">株式会社ベストリンクス</div>
            <!-- 👇 ここにGoogleフォームのURLを設定してください -->
            <a href="https://forms.gle/YOUR_GOOGLE_FORM_URL" target="_blank" class="header-cta">無料相談はこちら</a>
        </div>
    </header>

    <!-- ヒーローセクション -->
    <section class="hero">
        <div class="container">
            <h1>住宅ローン借り換えで<br><span class="highlight">リノベーション資金を調達</span></h1>
            <p class="subtitle">金利差を活用して、夢の住まいを実現しませんか？</p>
            <p>現在の住宅ローンを見直すだけで、リノベーション資金が手に入る可能性があります</p>
        </div>
    </section>

    <!-- 診断ツールセクション -->
    <section class="diagnosis">
        <div class="container">
            <h2>🏠 簡易住宅ローン診断</h2>
            <div class="diagnosis-form">
                <div class="form-group">
                    <label for="currentBalance">現在の住宅ローン残高（万円）</label>
                    <input type="number" id="currentBalance" placeholder="例：2500">
                </div>
                <div class="form-group">
                    <label for="currentRate">現在の金利（%）</label>
                    <input type="number" id="currentRate" step="0.1" placeholder="例：1.5">
                </div>
                <div class="form-group">
                    <label for="remainingYears">残り返済期間（年）</label>
                    <input type="number" id="remainingYears" placeholder="例：25">
                </div>
                <div class="form-group">
                    <label for="renovationBudget">リノベーション予算（万円）</label>
                    <input type="number" id="renovationBudget" placeholder="例：500">
                </div>
                <div class="form-group">
                    <label for="income">年収（万円）</label>
                    <input type="number" id="income" placeholder="例：600">
                </div>
                <button class="diagnosis-btn" onclick="calculateDiagnosis()">診断結果を見る</button>
                
                <div class="result" id="diagnosisResult">
                    <h3>✨ 診断結果</h3>
                    <div class="result-item">
                        <span>借り換え後の想定金利</span>
                        <span class="result-value" id="newRate">0.8%</span>
                    </div>
                    <div class="result-item">
                        <span>月々の返済軽減額</span>
                        <span class="result-value" id="monthlySavings">約15,000円</span>
                    </div>
                    <div class="result-item">
                        <span>総返済軽減額</span>
                        <span class="result-value" id="totalSavings">約450万円</span>
                    </div>
                    <div class="result-item">
                        <span>リノベーション後の月額返済</span>
                        <span class="result-value" id="newMonthlyPayment">約95,000円</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- メリットセクション -->
    <section class="benefits">
        <div class="container">
            <h2>住宅ローン借り換えの3つのメリット</h2>
            <div class="benefits-grid">
                <div class="benefit-card fade-in">
                    <div class="benefit-icon">💰</div>
                    <h3>低金利でリノベーション資金を調達</h3>
                    <p>リフォームローン（金利2-5%）に比べて、住宅ローン金利（0.5-1.5%）でリノベーション資金を借りられます。</p>
                </div>
                <div class="benefit-card fade-in">
                    <div class="benefit-icon">📋</div>
                    <h3>ローンを一本化してスッキリ管理</h3>
                    <p>複数のローンを管理する手間がなくなり、返済計画が立てやすくなります。団体信用生命保険も一つで済みます。</p>
                </div>
                <div class="benefit-card fade-in">
                    <div class="benefit-icon">🏡</div>
                    <h3>最長35年の長期返済で月額負担軽減</h3>
                    <p>リフォームローンは通常10-15年ですが、住宅ローンなら最長35年。月々の返済額を大幅に抑えられます。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 事例セクション -->
    <section class="cases">
        <div class="container">
            <h2>実際の成功事例</h2>
            <div
