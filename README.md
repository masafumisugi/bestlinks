<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>実質無料でリノベができる！住宅ローン借り換えリノベーション | 株式会社ベストリンクス</title>
    <meta name="description" content="15年以上前に住宅を購入されたご家族へ。住宅ローン借り換えで実質無料リノベーション！毎月の支払いを変えずに理想の住まいを実現しませんか？">
    <style>
        :root {
            --vh: 1vh;
            --primary-color: #2c5aa0;
            --accent-color: #ff6b35;
            --text-color: #333;
            --bg-light: #f8f9fa;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            -webkit-text-size-adjust: 100%;
            -webkit-font-smoothing: antialiased;
            opacity: 0;
            animation: fadeInBody 0.5s ease-in-out forwards;
        }

        @keyframes fadeInBody {
            to { opacity: 1; }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* ヘッダー */
        .header {
            background: var(--white);
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
            color: var(--primary-color);
        }

        .header-cta {
            background: var(--accent-color);
            color: white !important;
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            font-weight: bold;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            cursor: pointer;
            min-height: 44px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .header-cta:hover {
            background: #e55a2b;
            transform: translateY(-2px);
            color: white !important;
        }

        /* ファーストビュー */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 600"><rect fill="%234a90e2" width="1200" height="600"/><text x="600" y="280" text-anchor="middle" font-size="36" fill="white">リビング空間</text><text x="600" y="320" text-anchor="middle" font-size="18" fill="white">理想の住まいをイメージ</text></svg>');
            background-size: cover;
            background-position: center;
            background-attachment: scroll;
            color: white;
            padding: 140px 0 100px;
            text-align: center;
            margin-top: 70px;
            position: relative;
            min-height: 100vh;
            display: flex;
            align-items: center;
        }

        .hero-content {
            width: 100%;
        }

        .hero-badge {
            background: var(--accent-color);
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 16px;
            margin-bottom: 30px;
            display: inline-block;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            line-height: 1.2;
            font-weight: bold;
        }

        .hero .subtitle {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #ffeb3b;
            font-weight: bold;
        }

        .hero .description {
            font-size: 1.2rem;
            margin-bottom: 40px;
            opacity: 0.9;
        }

        .hero-cta {
            background: linear-gradient(45deg, var(--accent-color), #f7931e);
            color: white;
            padding: 20px 50px;
            border: none;
            border-radius: 50px;
            font-size: 20px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
            box-shadow: 0 10px 30px rgba(255, 107, 53, 0.4);
            min-height: 60px;
            line-height: 1.2;
        }

        .hero-cta:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(255, 107, 53, 0.6);
        }

        /* セクション共通スタイル */
        .section {
            padding: 80px 0;
        }

        .section h2 {
            text-align: center;
            font-size: 2.8rem;
            margin-bottom: 20px;
            color: var(--primary-color);
            line-height: 1.3;
        }

        .section-desc {
            text-align: center;
            font-size: 1.2rem;
            margin-bottom: 60px;
            color: #666;
            line-height: 1.6;
        }

        /* メリットセクション */
        .benefits-section {
            background: var(--white);
        }

        .benefits-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .benefits-list {
            list-style: none;
        }

        .benefits-list li {
            margin-bottom: 25px;
            padding-left: 40px;
            position: relative;
            font-size: 1.1rem;
            line-height: 1.6;
        }

        .benefits-list li::before {
            content: "✓";
            position: absolute;
            left: 0;
            top: 0;
            color: var(--accent-color);
            font-weight: bold;
            font-size: 1.5rem;
        }

        .benefits-image {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 15px;
            padding: 40px;
            text-align: center;
            color: #666;
            min-height: 300px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            border: 2px solid #e9ecef;
        }

        /* お客様の声 */
        .testimonial {
            background: var(--bg-light);
        }

        .testimonial-card {
            background: var(--white);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            max-width: 800px;
            margin: 0 auto;
            position: relative;
        }

        .testimonial-quote {
            font-size: 1.2rem;
            line-height: 1.8;
            margin-bottom: 20px;
            font-style: italic;
        }

        .testimonial-author {
            text-align: right;
            font-weight: bold;
            color: var(--primary-color);
        }

        /* 施工事例 */
        .portfolio {
            background: var(--white);
        }

        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
        }

        .portfolio-item {
            background: var(--white);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .portfolio-item:hover {
            transform: translateY(-10px);
        }

        .portfolio-image {
            background: linear-gradient(135deg, #4a90e2 0%, #667eea 100%);
            height: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 16px;
        }

        .portfolio-content {
            padding: 25px;
        }

        .portfolio-title {
            font-size: 1.3rem;
            font-weight: bold;
            color: var(--primary-color);
            margin-bottom: 10px;
        }

        /* 選ばれる理由 */
        .reasons {
            background: var(--bg-light);
        }

        .reasons-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
        }

        .reason-card {
            background: var(--white);
            padding: 40px 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .reason-card:hover {
            transform: translateY(-10px);
        }

        .reason-icon {
            font-size: 4rem;
            margin-bottom: 20px;
            color: var(--accent-color);
        }

        .reason-title {
            font-size: 1.4rem;
            font-weight: bold;
            margin-bottom: 15px;
            color: var(--primary-color);
        }

        .reason-desc {
            color: #666;
            line-height: 1.6;
        }

        /* 診断ツール */
        .diagnosis-tool {
            background: var(--white);
        }

        .diagnosis-form {
            background: var(--bg-light);
            padding: 50px;
            border-radius: 20px;
            max-width: 800px;
            margin: 0 auto;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .form-row {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 25px;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
            color: var(--text-color);
            font-size: 14px;
        }

        .form-group input {
            width: 100%;
            padding: 15px;
            border: 2px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s ease;
            -webkit-appearance: none;
            min-height: 50px;
        }

        .form-group input:focus {
            outline: none;
            border-color: var(--primary-color);
        }

        .diagnosis-btn {
            background: linear-gradient(45deg, var(--accent-color), #f7931e);
            color: white;
            padding: 18px 40px;
            border: none;
            border-radius: 50px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            transition: all 0.3s ease;
            min-height: 60px;
            -webkit-appearance: none;
        }

        .diagnosis-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(255, 107, 53, 0.3);
        }

        .diagnosis-result {
            margin-top: 30px;
            padding: 30px;
            background: var(--white);
            border-radius: 15px;
            border-left: 5px solid #28a745;
            display: none;
        }

        .diagnosis-result.show {
            display: block;
            animation: slideDown 0.5s ease;
        }

        @keyframes slideDown {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .result-highlight {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--accent-color);
            text-align: center;
            margin-bottom: 20px;
        }

        /* 特典セクション */
        .special-offer {
            background: linear-gradient(135deg, var(--primary-color) 0%, #667eea 100%);
            color: white;
            text-align: center;
        }

        .offer-badge {
            background: var(--accent-color);
            color: white;
            padding: 15px 40px;
            border-radius: 50px;
            font-size: 1.3rem;
            font-weight: bold;
            margin-bottom: 30px;
            display: inline-block;
            animation: pulse 2s infinite;
        }

        .offer-description {
            font-size: 1.3rem;
            margin-bottom: 40px;
            line-height: 1.6;
        }

        /* お問い合わせフォーム */
        .contact {
            background: var(--bg-light);
        }

        .contact-form-container {
            max-width: 800px;
            margin: 0 auto;
            background: var(--white);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            overflow: hidden;
        }

        .form-header {
            background: var(--primary-color);
            color: white;
            padding: 30px;
            text-align: center;
        }

        .form-header h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .form-header p {
            opacity: 0.9;
        }

        /* Googleフォーム埋め込み用スタイル */
        .google-form-wrapper {
            position: relative;
            width: 100%;
            padding: 0;
        }

        .google-form-iframe {
            width: 100%;
            border: none;
            min-height: 985px;
            background: white;
        }

        /* フッター */
        .footer {
            background: #333;
            color: white;
            padding: 50px 0 30px;
            text-align: center;
        }

        .footer-content {
            margin-bottom: 30px;
        }

        .footer h3 {
            margin-bottom: 15px;
            color: var(--accent-color);
            font-size: 1.5rem;
        }

        .footer p {
            margin-bottom: 10px;
            line-height: 1.6;
        }

        .phone-highlight {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--accent-color);
            margin: 20px 0;
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

        /* ===== スマートフォン完全対応 ===== */

        /* タブレット対応 */
        @media (max-width: 1024px) {
            .container {
                padding: 0 15px;
            }

            .hero h1 {
                font-size: 3rem;
            }

            .diagnosis-form {
                padding: 40px 30px;
            }

            .google-form-iframe {
                min-height: 900px;
            }
        }

        /* スマートフォン対応 */
        @media (max-width: 768px) {
            /* ヘッダー */
            .header-content {
                flex-direction: column;
                gap: 12px;
                padding: 12px 15px;
            }

            .logo {
                font-size: 18px;
            }

            .header-cta {
                padding: 12px 20px;
                font-size: 14px;
                min-height: 44px;
                width: 100%;
                max-width: 250px;
            }

            /* ヒーローセクション */
            .hero {
                padding: 120px 0 80px;
                margin-top: 100px;
                min-height: calc(100vh - 100px);
            }

            .hero-badge {
                font-size: 14px;
                padding: 10px 20px;
                margin-bottom: 20px;
            }

            .hero h1 {
                font-size: 2.5rem;
                line-height: 1.2;
                margin-bottom: 15px;
            }

            .hero .subtitle {
                font-size: 1.4rem;
                margin-bottom: 12px;
            }

            .hero .description {
                font-size: 1.1rem;
                margin-bottom: 30px;
            }

            .hero-cta {
                padding: 15px 30px;
                font-size: 16px;
                min-height: 55px;
                width: 90%;
                max-width: 300px;
            }

            /* セクション共通 */
            .section {
                padding: 60px 0;
            }

            .section h2 {
                font-size: 2.2rem;
                margin-bottom: 15px;
                line-height: 1.3;
            }

            .section-desc {
                font-size: 1.1rem;
                margin-bottom: 40px;
                padding: 0 10px;
            }

            /* メリットセクション */
            .benefits-content {
                grid-template-columns: 1fr;
                gap: 40px;
            }

            .benefits-list li {
                font-size: 1rem;
                margin-bottom: 20px;
                padding-left: 35px;
            }

            .benefits-list li::before {
                font-size: 1.3rem;
            }

            .benefits-image {
                min-height: 200px;
                padding: 30px 20px;
            }

            /* お客様の声 */
            .testimonial-card {
                padding: 30px 20px;
                margin: 0 10px;
            }

            .testimonial-quote {
                font-size: 1.1rem;
                line-height: 1.7;
            }

            /* 施工事例 */
            .portfolio-grid {
                grid-template-columns: 1fr;
                gap: 30px;
            }

            .portfolio-item {
                margin: 0 10px;
            }

            .portfolio-image {
                height: 200px;
            }

            .portfolio-content {
                padding: 20px;
            }

            .portfolio-title {
                font-size: 1.2rem;
            }

            /* 選ばれる理由 */
            .reasons-grid {
                grid-template-columns: 1fr;
                gap: 30px;
            }

            .reason-card {
                padding: 30px 20px;
                margin: 0 10px;
            }

            .reason-icon {
                font-size: 3rem;
            }

            .reason-title {
                font-size: 1.3rem;
            }

            .reason-desc {
                font-size: 14px;
            }

            /* 診断ツール */
            .form-row {
                grid-template-columns: 1fr;
                gap: 15px;
            }

            .diagnosis-form {
                padding: 30px 20px;
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
                min-height: 48px;
            }

            .diagnosis-btn {
                padding: 15px 30px;
                font-size: 16px;
                min-height: 55px;
            }

            .diagnosis-result {
                padding: 20px;
                margin-top: 20px;
            }

            .result-highlight {
                font-size: 1.3rem;
            }

            /* 特典セクション */
            .offer-badge {
                font-size: 1.1rem;
                padding: 12px 25px;
                margin-bottom: 20px;
            }

            .offer-description {
                font-size: 1.1rem;
                margin-bottom: 30px;
                padding: 0 10px;
            }

            /* お問い合わせフォーム（スマホ対応） */
            .contact-form-container {
                margin: 0 10px;
                border-radius: 15px;
            }

            .form-header {
                padding: 25px 20px;
            }

            .form-header h3 {
                font-size: 1.3rem;
            }

            .form-header p {
                font-size: 14px;
            }

            .google-form-iframe {
                min-height: 800px;
            }

            /* フッター */
            .footer {
                padding: 40px 0 20px;
            }

            .footer h3 {
                font-size: 1.3rem;
            }

            .footer p {
                font-size: 14px;
            }

            .phone-highlight {
                font-size: 1.5rem;
            }
        }

        /* 小さなスマートフォン対応 */
        @media (max-width: 480px) {
            .container {
                padding: 0 10px;
            }

            .hero h1 {
                font-size: 2rem;
                line-height: 1.2;
            }

            .hero .subtitle {
                font-size: 1.2rem;
            }

            .hero .description {
                font-size: 1rem;
            }

            .hero-cta {
                padding: 12px 25px;
                font-size: 15px;
                width: 95%;
            }

            .section h2 {
                font-size: 1.8rem;
            }

            .section-desc {
                font-size: 1rem;
            }

            .diagnosis-form {
                padding: 20px 15px;
                margin: 0 5px;
            }

            .benefits-list li {
                font-size: 0.95rem;
            }

            .testimonial-card {
                padding: 25px 15px;
                margin: 0 5px;
            }

            .portfolio-item, .reason-card {
                margin: 0 5px;
            }

            .offer-description {
                font-size: 1rem;
            }

            .contact-form-container {
                margin: 0 5px;
            }

            .google-form-iframe {
                min-height: 700px;
            }
        }

        /* 横向きスマートフォン対応 */
        @media (max-width: 768px) and (orientation: landscape) {
            .hero {
                padding: 80px 0 60px;
                min-height: 90vh;
            }

            .hero h1 {
                font-size: 2.2rem;
            }

            .section {
                padding: 50px 0;
            }

            .benefits-content {
                grid-template-columns: repeat(2, 1fr);
                gap: 30px;
            }

            .reasons-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 25px;
            }

            .google-form-iframe {
                min-height: 600px;
            }
        }

        /* タッチデバイス用改善 */
        @media (hover: none) {
            .portfolio-item:hover,
            .reason-card:hover {
                transform: none;
            }

            .hero-cta:active,
            .header-cta:active,
            .diagnosis-btn:active {
                transform: scale(0.98);
                opacity: 0.8;
            }
        }

        /* iOS Safari対応 */
        @supports (-webkit-touch-callout: none) {
            .form-group input {
                font-size: 16px !important;
                -webkit-appearance: none;
                border-radius: 8px;
            }

            .diagnosis-btn, .hero-cta, .header-cta {
                -webkit-appearance: none;
                border: none;
            }

            .hero {
                background-attachment: scroll;
            }
        }

        /* スクロール改善 */
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

        /* パフォーマンス最適化 */
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
            <a href="#contact" class="header-cta">まずは無料相談してみる</a>
        </div>
    </header>

    <!-- ファーストビュー -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-badge">このサイトを見た方限定！</div>
                <h1>実質無料で<br>リノベができる！？</h1>
                <p class="subtitle">15年以上前に住宅を購入されたご家族へ</p>
                <p class="description">毎月の支払いを大きく変えずに、理想の住まいへ</p>
                <a href="#contact" class="hero-cta">まずは無料相談してみる</a>
            </div>
        </div>
    </section>

    <!-- メリットセクション -->
    <section class="benefits-section section">
        <div class="container">
            <h2>毎月の支払いはそのままに、理想の住まいへ</h2>
            <p class="section-desc">住宅ローン借り換えによるリノベーションで、新しい暮らしを始めませんか？</p>
            <div class="benefits-content">
                <div>
                    <ul class="benefits-list">
                        <li>最新の設備で、日々の暮らしがより快適に</li>
                        <li>間取りを自由にアレンジして、理想の空間を創出</li>
                        <li>住まいの価値を高め、将来の安心にも繋がる</li>
                        <li>断熱性の向上で、一年中快適な住まいと光熱費の削減</li>
                    </ul>
                </div>
                <div class="benefits-image">
                    <div style="font-size: 4rem; margin-bottom: 20px;">🏠</div>
                    <p><strong>新しいキッチンのイメージ</strong></p>
                    <p style="font-size: 14px; margin-top: 10px; color: #888;">最新設備で使いやすく美しいキッチン</p>
                </div>
            </div>
        </div>
    </section>

    <!-- お客様の声 -->
    <section class="testimonial section">
        <div class="container">
            <h2>実際にリノベーションされたお客様の声</h2>
            <div class="testimonial-card fade-in">
                <div class="testimonial-quote">
                    「築18年を越えた我が家でしたが、住宅ローンの借り換えを活用してフルリノベーションを実現できました。毎月の支払いはほとんど変わらないのに、まるで新築のような住まいに生まれ変わり、家族みんなが大満足しています。特にキッチ
