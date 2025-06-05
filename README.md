<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>実質無料でリノベができる！住宅ローン借り換えリノベーション | 株式会社ベストリンクス</title>
    <meta name="description" content="15年以上前に住宅を購入されたご家族へ。住宅ローン借り換えで実質無料リノベーション！毎月の支払いを変えずに理想の住まいを実現しませんか？">
    <style>
        :root {
            /* グレイッシュトーンカラーパレット */
            --primary-gray: #5a5a5a;
            --secondary-gray: #8a8a8a;
            --light-gray: #e8e8e8;
            --warm-gray: #f5f5f3;
            --charcoal: #3a3a3a;
            --accent-warm: #b89b7f;
            --accent-gold: #d4af37;
            --text-dark: #2a2a2a;
            --text-medium: #6a6a6a;
            --white: #ffffff;
            --soft-shadow: rgba(0,0,0,0.08);
            --border-light: rgba(0,0,0,0.1);
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
            color: var(--text-dark);
            -webkit-text-size-adjust: 100%;
            -webkit-font-smoothing: antialiased;
            background-color: var(--warm-gray);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 30px;
        }

        /* ヘッダー */
        .header {
            background: rgba(255,255,255,0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid var(--border-light);
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
            padding: 20px 30px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            font-size: 20px;
            font-weight: 300;
            color: var(--text-dark);
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        .header-cta {
            background: var(--charcoal);
            color: white !important;
            padding: 12px 30px;
            border: none;
            border-radius: 0;
            font-weight: 300;
            text-decoration: none;
            display: inline-block;
            transition: all 0.3s ease;
            cursor: pointer;
            min-height: 44px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 14px;
            letter-spacing: 0.5px;
        }

        .header-cta:hover {
            background: var(--primary-gray);
            color: white !important;
        }

        /* ファーストビュー */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.2)), url('https://cdn1.genspark.ai/user-upload-image/22_generated/19acffcf-9c2d-4637-b068-135a2b799609');
            background-size: cover;
            background-position: center;
            background-attachment: scroll;
            color: white;
            padding: 140px 0 120px;
            text-align: center;
            margin-top: 80px;
            position: relative;
            min-height: 90vh;
            display: flex;
            align-items: center;
        }

        .hero-content {
            width: 100%;
        }

        .hero-badge {
            background: var(--accent-gold);
            color: var(--text-dark);
            padding: 8px 24px;
            border-radius: 0;
            font-weight: 300;
            font-size: 13px;
            margin-bottom: 40px;
            display: inline-block;
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 30px;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
            line-height: 1.2;
            font-weight: 300;
            letter-spacing: 1px;
        }

        .hero .subtitle {
            font-size: 1.4rem;
            margin-bottom: 20px;
            opacity: 0.9;
            font-weight: 300;
            letter-spacing: 0.5px;
        }

        .hero .description {
            font-size: 1.1rem;
            margin-bottom: 50px;
            opacity: 0.85;
            font-weight: 300;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.8;
        }

        .hero-cta {
            background: var(--white);
            color: var(--text-dark);
            padding: 18px 50px;
            border: none;
            border-radius: 0;
            font-size: 16px;
            font-weight: 300;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
            min-height: 60px;
            line-height: 1.2;
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        .hero-cta:hover {
            background: var(--light-gray);
            transform: translateY(-2px);
            box-shadow: 0 8px 25px var(--soft-shadow);
        }

        /* セクション共通スタイル */
        .section {
            padding: 100px 0;
        }

        .section-header {
            text-align: center;
            margin-bottom: 80px;
        }

        .section h2 {
            font-size: 2.2rem;
            margin-bottom: 20px;
            color: var(--text-dark);
            line-height: 1.4;
            font-weight: 300;
            letter-spacing: 1px;
        }

        .section-desc {
            font-size: 1rem;
            color: var(--text-medium);
            line-height: 1.8;
            max-width: 600px;
            margin: 0 auto;
        }

        /* メリットセクション */
        .benefits-section {
            background: var(--white);
        }

        .benefits-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 80px;
            align-items: center;
        }

        .benefits-list {
            list-style: none;
        }

        .benefits-list li {
            margin-bottom: 30px;
            padding-left: 30px;
            position: relative;
            font-size: 1rem;
            line-height: 1.8;
            color: var(--text-medium);
        }

        .benefits-list li::before {
            content: "—";
            position: absolute;
            left: 0;
            top: 0;
            color: var(--accent-warm);
            font-weight: 300;
            font-size: 1.2rem;
        }

        .benefits-image {
            background: url('https://cdn1.genspark.ai/user-upload-image/22_generated/5c3216e1-33cd-411b-89a8-59fae3c5109d');
            background-size: cover;
            background-position: center;
            min-height: 400px;
            position: relative;
            overflow: hidden;
        }

        .benefits-image::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(transparent 60%, rgba(0,0,0,0.4));
        }

        .benefits-image-content {
            position: absolute;
            bottom: 30px;
            left: 30px;
            right: 30px;
            color: white;
            z-index: 2;
        }

        .benefits-image-content h3 {
            font-size: 1.1rem;
            font-weight: 300;
            letter-spacing: 0.5px;
        }

        /* お客様の声 */
        .testimonial {
            background: var(--warm-gray);
        }

        .testimonial-card {
            background: var(--white);
            padding: 60px;
            max-width: 800px;
            margin: 0 auto;
            position: relative;
            border: 1px solid var(--border-light);
        }

        .testimonial-quote {
            font-size: 1.1rem;
            line-height: 2;
            margin-bottom: 30px;
            color: var(--text-medium);
            font-style: normal;
            font-weight: 300;
        }

        .testimonial-author {
            text-align: right;
            font-weight: 300;
            color: var(--text-dark);
            font-size: 0.9rem;
            letter-spacing: 0.5px;
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
            overflow: hidden;
            transition: transform 0.3s ease;
            border: 1px solid var(--border-light);
        }

        .portfolio-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px var(--soft-shadow);
        }

        .portfolio-image {
            height: 280px;
            background-size: cover;
            background-position: center;
            position: relative;
        }

        .portfolio-content {
            padding: 30px;
        }

        .portfolio-title {
            font-size: 1.1rem;
            font-weight: 300;
            color: var(--text-dark);
            margin-bottom: 15px;
            letter-spacing: 0.5px;
        }

        .portfolio-desc {
            color: var(--text-medium);
            line-height: 1.7;
            font-size: 0.9rem;
        }

        /* 選ばれる理由 */
        .reasons {
            background: var(--warm-gray);
        }

        .reasons-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 40px;
        }

        .reason-card {
            background: var(--white);
            padding: 40px 30px;
            text-align: center;
            transition: transform 0.3s ease;
            border: 1px solid var(--border-light);
        }

        .reason-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px var(--soft-shadow);
        }

        .reason-icon {
            font-size: 2.5rem;
            margin-bottom: 25px;
            color: var(--accent-warm);
        }

        .reason-title {
            font-size: 1.2rem;
            font-weight: 300;
            margin-bottom: 20px;
            color: var(--text-dark);
            letter-spacing: 0.5px;
        }

        .reason-desc {
            color: var(--text-medium);
            line-height: 1.7;
            font-size: 0.9rem;
        }

        /* 診断ツール */
        .diagnosis-tool {
            background: var(--white);
        }

        .diagnosis-form {
            background: var(--warm-gray);
            padding: 50px;
            max-width: 700px;
            margin: 0 auto;
            border: 1px solid var(--border-light);
        }

        .form-row {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 25px;
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 25px;
        }

        .form-group label {
            display: block;
            margin-bottom: 10px;
            font-weight: 300;
            color: var(--text-dark);
            font-size: 14px;
            letter-spacing: 0.5px;
        }

        .form-group input {
            width: 100%;
            padding: 15px;
            border: 1px solid var(--border-light);
            border-radius: 0;
            font-size: 16px;
            transition: border-color 0.3s ease;
            -webkit-appearance: none;
            min-height: 50px;
            background: var(--white);
            font-weight: 300;
        }

        .form-group input:focus {
            outline: none;
            border-color: var(--primary-gray);
        }

        .diagnosis-btn {
            background: var(--charcoal);
            color: white;
            padding: 18px 40px;
            border: none;
            border-radius: 0;
            font-size: 14px;
            font-weight: 300;
            cursor: pointer;
            width: 100%;
            transition: all 0.3s ease;
            min-height: 60px;
            -webkit-appearance: none;
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        .diagnosis-btn:hover {
            background: var(--primary-gray);
        }

        .diagnosis-result {
            margin-top: 30px;
            padding: 40px;
            background: var(--white);
            border-left: 3px solid var(--accent-warm);
            display: none;
        }

        .diagnosis-result.show {
            display: block;
            animation: fadeIn 0.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .result-highlight {
            font-size: 1.5rem;
            font-weight: 300;
            color: var(--text-dark);
            text-align: center;
            margin-bottom: 20px;
            letter-spacing: 0.5px;
        }

        /* 特典セクション */
        .special-offer {
            background: var(--charcoal);
            color: white;
            text-align: center;
        }

        .offer-badge {
            background: var(--accent-gold);
            color: var(--text-dark);
            padding: 12px 40px;
            border-radius: 0;
            font-size: 1rem;
            font-weight: 300;
            margin-bottom: 30px;
            display: inline-block;
            letter-spacing: 1px;
            text-transform: uppercase;
        }

        .offer-description {
            font-size: 1.1rem;
            margin-bottom: 40px;
            line-height: 1.8;
            font-weight: 300;
            opacity: 0.9;
        }

        /* お問い合わせフォーム */
        .contact {
            background: var(--warm-gray);
        }

        .contact-form-container {
            max-width: 800px;
            margin: 0 auto;
            background: var(--white);
            overflow: hidden;
            border: 1px solid var(--border-light);
        }

        .form-header {
            background: var(--primary-gray);
            color: white;
            padding: 40px;
            text-align: center;
        }

        .form-header h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            font-weight: 300;
            letter-spacing: 1px;
        }

        .form-header p {
            opacity: 0.9;
            font-size: 0.9rem;
            font-weight: 300;
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
            background: var(--charcoal);
            color: white;
            padding: 60px 0 40px;
            text-align: center;
        }

        .footer-content {
            margin-bottom: 40px;
        }

        .footer h3 {
            margin-bottom: 20px;
            color: var(--accent-warm);
            font-size: 1.2rem;
            font-weight: 300;
            letter-spacing: 1px;
        }

        .footer p {
            margin-bottom: 8px;
            line-height: 1.8;
            font-size: 0.9rem;
            opacity: 0.8;
            font-weight: 300;
        }

        .phone-highlight {
            font-size: 1.4rem;
            font-weight: 300;
            color: var(--accent-gold);
            margin: 20px 0;
            letter-spacing: 1px;
        }

        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.8s ease;
        }

        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* ===== スマートフォン完全対応 ===== */

        /* タブレット対応 */
        @media (max-width: 1024px) {
            .container {
                padding: 0 20px;
            }

            .hero h1 {
                font-size: 3rem;
            }

            .google-form-iframe {
                min-height: 900px;
            }
        }

        /* スマートフォン対応 */
        @media (max-width: 768px) {
            .container {
                padding: 0 15px;
            }

            /* ヘッダー */
            .header-content {
                flex-direction: column;
                gap: 15px;
                padding: 15px 20px;
            }

            .logo {
                font-size: 18px;
            }

            .header-cta {
                padding: 12px 25px;
                font-size: 13px;
                width: 100%;
                max-width: 250px;
            }

            /* ヒーローセクション */
            .hero {
                padding: 100px 0 80px;
                margin-top: 100px;
                min-height: calc(100vh - 100px);
            }

            .hero-badge {
                font-size: 12px;
                padding: 6px 20px;
                margin-bottom: 30px;
            }

            .hero h1 {
                font-size: 2.2rem;
                line-height: 1.3;
                margin-bottom: 25px;
            }

            .hero .subtitle {
                font-size: 1.2rem;
                margin-bottom: 15px;
            }

            .hero .description {
                font-size: 1rem;
                margin-bottom: 40px;
                padding: 0 10px;
            }

            .hero-cta {
                padding: 15px 35px;
                font-size: 14px;
                min-height: 55px;
                width: 80%;
                max-width: 280px;
            }

            /* セクション共通 */
            .section {
                padding: 80px 0;
            }

            .section-header {
                margin-bottom: 60px;
            }

            .section h2 {
                font-size: 2rem;
                margin-bottom: 15px;
                line-height: 1.4;
            }

            .section-desc {
                font-size: 0.95rem;
                padding: 0 10px;
            }

            /* メリットセクション */
            .benefits-content {
                grid-template-columns: 1fr;
                gap: 50px;
            }

            .benefits-list li {
                font-size: 0.95rem;
                margin-bottom: 25px;
                padding-left: 25px;
            }

            .benefits-image {
                min-height: 300px;
                order: -1;
            }

            .benefits-image-content {
                bottom: 20px;
                left: 20px;
                right: 20px;
            }

            /* お客様の声 */
            .testimonial-card {
                padding: 40px 25px;
                margin: 0 10px;
            }

            .testimonial-quote {
                font-size: 1rem;
                line-height: 1.8;
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
                height: 220px;
            }

            .portfolio-content {
                padding: 25px;
            }

            .portfolio-title {
                font-size: 1rem;
            }

            .portfolio-desc {
                font-size: 0.85rem;
            }

            /* 選ばれる理由 */
            .reasons-grid {
                grid-template-columns: 1fr;
                gap: 30px;
            }

            .reason-card {
                padding: 30px 25px;
                margin: 0 10px;
            }

            .reason-icon {
                font-size: 2.2rem;
            }

            .reason-title {
                font-size: 1.1rem;
            }

            .reason-desc {
                font-size: 0.85rem;
            }

            /* 診断ツール */
            .form-row {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .diagnosis-form {
                padding: 40px 25px;
                margin: 0 10px;
            }

            .form-group {
                margin-bottom: 20px;
            }

            .form-group label {
                font-size: 13px;
                margin-bottom: 8px;
            }

            .form-group input {
                padding: 12px;
                font-size: 16px;
                min-height: 48px;
            }

            .diagnosis-btn {
                padding: 15px 30px;
                font-size: 13px;
                min-height: 55px;
            }

            .diagnosis-result {
                padding: 30px 20px;
                margin-top: 25px;
            }

            .result-highlight {
                font-size: 1.3rem;
            }

            /* 特典セクション */
            .offer-badge {
                font-size: 0.9rem;
                padding: 10px 30px;
                margin-bottom: 25px;
            }

            .offer-description {
                font-size: 1rem;
                margin-bottom: 35px;
                padding: 0 15px;
            }

            /* お問い合わせフォーム */
            .contact-form-container {
                margin: 0 10px;
            }

            .form-header {
                padding: 30px 25px;
            }

            .form-header h3 {
                font-size: 1.2rem;
            }

            .form-header p {
                font-size: 0.85rem;
            }

            .google-form-iframe {
                min-height: 800px;
            }

            /* フッター */
            .footer {
                padding: 50px 0 30px;
            }

            .footer h3 {
                font-size: 1.1rem;
            }

            .footer p {
                font-size: 0.85rem;
            }

            .phone-highlight {
                font-size: 1.2rem;
            }
        }

        /* 小さなスマートフォン対応 */
        @media (max-width: 480px) {
            .container {
                padding: 0 10px;
            }

            .hero h1 {
                font-size: 1.9rem;
                line-height: 1.3;
            }

            .hero .subtitle {
                font-size: 1.1rem;
            }

            .hero .description {
                font-size: 0.9rem;
            }

            .hero-cta {
                padding: 12px 30px;
                font-size: 13px;
                width: 90%;
            }

            .section h2 {
                font-size: 1.7rem;
            }

            .section-desc {
                font-size: 0.9rem;
            }

            .diagnosis-form {
                padding: 30px 20px;
                margin: 0 5px;
            }

            .testimonial-card {
                padding: 30px 20px;
                margin: 0 5px;
            }

            .portfolio-item, .reason-card {
                margin: 0 5px;
            }

            .offer-description {
                font-size: 0.95rem;
            }

            .contact-form-container {
                margin: 0 5px;
            }

            .google-form-iframe {
                min-height: 750px;
            }
        }

        /* 横向きスマートフォン対応 */
        @media (max-width: 768px) and (orientation: landscape) {
            .hero {
                padding: 80px 0 60px;
                min-height: 85vh;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .section {
                padding: 60px 0;
            }

            .benefits-content {
                grid-template-columns: repeat(2, 1fr);
                gap: 40px;
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
            }

            .diagnosis-btn, .hero-cta, .header-cta {
                -webkit-appearance: none;
                border: none;
            }

            .hero {
                background-attachment: scroll;
            }
        }
    </style>
</head>
<body>
    <!-- ヘッダー -->
    <header class="header">
        <div class="header-content">
            <div class="logo">BEST LINKS</div>
            <a href="#contact" class="header-cta">無料相談</a>
        </div>
    </header>

    <!-- ファーストビュー -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <div class="hero-badge">LIMITED OFFER</div>
                <h1>実質無料で<br>リノベができる</h1>
                <p class="subtitle">15年以上前に住宅を購入されたご家族へ</p>
                <p class="description">住宅ローンの借り換えを活用することで、毎月の支払いを大きく変えずに理想の住まいを実現できる可能性があります。</p>
                <a href="#contact" class="hero-cta">相談を始める</a>
            </div>
        </div>
    </section>

    <!-- メリットセクション -->
    <section class="benefits-section section">
        <div class="container">
            <div class="section-header">
                <h2>毎月の支払いはそのままに、理想の住まいへ</h2>
                <p class="section-desc">住宅ローン借り換えによるリノベーションで、新しい暮らしを始めませんか？長年培ってきた経験と技術で、お客様の理想を形にいたします。</p>
            </div>
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
                    <div
