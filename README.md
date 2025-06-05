<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>住宅ローン借り換えでリノベーション資金を調達 | 株式会社ベストリンクス</title>
    <meta name="description" content="住宅ローンの借り換えでリノベーション資金を賢く調達。金利差を活用して夢の住まいを実現しませんか？簡易診断ツールで今すぐメリットをチェック！">
    <style>
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
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 25px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .header-cta:hover {
            background: #e55a2b;
            transform: translateY(-2px);
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

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: rgba(255,255,255,0.1);
            padding: 40px;
            border-radius: 15px;
            backdrop-filter: blur(10px);
        }

        .contact-form .form-group input,
        .contact-form .form-group textarea {
            background: rgba(255,255,255,0.9);
            border: none;
        }

        .contact-form textarea {
            height: 120px;
            resize: vertical;
        }

        .contact-btn {
            background: #ff6b35;
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

        .contact-btn:hover {
            background: #e55a2b;
            transform: translateY(-3px);
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

        /* レスポンシブ対応 */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }

            .hero .subtitle {
                font-size: 1.2rem;
            }

            .diagnosis-form {
                padding: 30px 20px;
            }

            .company-content {
                grid-template-columns: 1fr;
            }

            .header-content {
                flex-direction: column;
                gap: 15px;
            }

            .case-grid {
                grid-template-columns: 1fr;
            }
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
    </style>
</head>
<body>
    <header class="header">
        <div class="header-content">
            <div class="logo">株式会社ベストリンクス</div>
            <button class="header-cta" onclick="scrollToContact()">無料相談はこちら</button>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>住宅ローン借り換えで<br><span class="highlight">リノベーション資金を調達</span></h1>
            <p class="subtitle">金利差を活用して、夢の住まいを実現しませんか？</p>
            <p>現在の住宅ローンを見直すだけで、リノベーション資金が手に入る可能性があります</p>
        </div>
    </section>

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
                    <div style="margin-top: 20px; padding: 15px; background: #e8f5e8; border-radius: 8px; text-align: center;">
                        <strong>🎉 借り換えメリットでリノベーション資金を確保できる可能性があります！</strong>
                    </div>
                </div>
            </div>
        </div>
    </section>

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

    <section class="cases">
        <div class="container">
            <h2>実際の成功事例</h2>
            <div class="case-grid">
                <div class="case-card fade-in">
                    <h3>築30年超のマンションを秘密基地風に（30代・男性）</h3>
                    <div class="case-details">
                        <div class="case-detail">
                            <span>ローン残高：</span>
                            <span>2,200万円</span>
                        </div>
                        <div class="case-detail">
                            <span>借り換え前金利：</span>
                            <span>1.8%</span>
                        </div>
                        <div class="case-detail">
                            <span>借り換え後金利：</span>
                            <span>0.9%</span>
                        </div>
                        <div class="case-detail">
                            <span>リノベーション予算：</span>
                            <span>600万円</span>
                        </div>
                    </div>
                    <div class="case-result">
                        月々18,000円の負担軽減＋理想の住まいを実現！
                    </div>
                </div>
                <div class="case-card fade-in">
                    <h3>憧れのコの字型キッチン（30代・女性）</h3>
                    <div class="case-details">
                        <div class="case-detail">
                            <span>ローン残高：</span>
                            <span>1,800万円</span>
                        </div>
                        <div class="case-detail">
                            <span>借り換え前金利：</span>
                            <span>2.1%</span>
                        </div>
                        <div class="case-detail">
                            <span>借り換え後金利：</span>
                            <span>0.7%</span>
                        </div>
                        <div class="case-detail">
                            <span>リノベーション予算：</span>
                            <span>800万円</span>
                        </div>
                    </div>
                    <div class="case-result">
                        月々22,000円の負担軽減＋スケルトンリノベで大満足！
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="services">
        <div class="container">
            <h2>ベストリンクスのリノベーションサービス</h2>
            <div class="service-grid">
                <div class="service-card fade-in">
                    <h3>🏠 内装リフォーム</h3>
                    <p>クロス張替え、フローリング施工で居住空間を快適に変えます。</p>
                </div>
                <div class="service-card fade-in">
                    <h3>🚿 水回りリフォーム</h3>
                    <p>キッチン、バスルーム、トイレ、洗面所の設備更新をお任せください。</p>
                </div>
                <div class="service-card fade-in">
                    <h3>🏗️ 増改築リフォーム</h3>
                    <p>部屋の増築や拡張、和室から洋室への変更など柔軟に対応。</p>
                </div>
                <div class="service-card fade-in">
                    <h3>🏪 店舗リフォーム</h3>
                    <p>内外装工事から集客力アップのデザインまで一貫してサポート。</p>
                </div>
            </div>
        </div>
    </section>

    <section class="company">
        <div class="container">
            <h2>信頼と実績のベストリンクス</h2>
            <div class="company-content">
                <div class="company-image">
                    <div style="background: #f0f0f0; padding: 60px; border-radius: 15px; text-align: center; color: #666;">
                        <div style="font-size: 4rem; margin-bottom: 20px;">🏢</div>
                        <p>関西一円で愛されるリフォーム専門会社</p>
                    </div>
                </div>
                <div class="company-info">
                    <h3>関西地域のリフォーム・リノベーションのプロフェッショナル</h3>
                    <p>大阪市・神戸市を中心に関西一円でリペア工事とリフォーム・リノベーション事業を展開。熟練した腕を持つ職人が多数在籍し、スピーディーかつクオリティの高い仕事をお約束いたします。</p>
                    <div class="company-stats">
                        <div class="stat-card">
                            <div class="stat-number">15+</div>
                            <div class="stat-label">年の実績</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number">1000+</div>
                            <div class="stat-label">施工実績</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number">98%</div>
                            <div class="stat-label">顧客満足度</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <div class="container">
            <h2>無料相談・お問い合わせ</h2>
            <div class="contact-form">
                <form id="contactForm" onsubmit="submitForm(event)">
                    <div class="form-group">
                        <label for="name">お名前 *</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">メールアドレス *</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="phone">電話番号</label>
                        <input type="tel" id="phone" name="phone">
                    </div>
                    <div class="form-group">
                        <label for="message">ご相談内容</label>
                        <textarea id="message" name="message" placeholder="リノベーションのご希望や住宅ローンの現状など、お気軽にご相談ください"></textarea>
                    </div>
                    <button type="submit" class="contact-btn">無料相談を申し込む</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div>
                    <h3>株式会社ベストリンクス</h3>
                    <p>〒533-0033<br>大阪府大阪市東淀川区東中島2-26-10<br>ユウアイビル3F</p>
                    <p>TEL: 06-6657-5092<br>営業時間: 9:30〜17:00</p>
                </div>
                <div>
                    <h3>サービス</h3>
                    <div class="footer-links">
                        <a href="#diagnosis">住宅ローン診断</a>
                        <a href="#services">リノベーション</a>
                        <a href="#contact">無料相談</a>
                        <a href="#">リペア工事</a>
                    </div>
                </div>
                <div>
                    <h3>会社情報</h3>
                    <div class="footer-links">
                        <a href="#">会社概要</a>
                        <a href="#">施工実績</a>
                        <a href="#">プライバシーポリシー</a>
                        <a href="#">お問い合わせ</a>
                    </div>
                </div>
            </div>
            <p>&copy; 2024 株式会社ベストリンクス. All rights reserved.</p>
        </div>
    </footer>

    <script>
        function scrollToContact() {
            document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
        }

        function calculateDiagnosis() {
            const currentBalance = parseFloat(document.getElementById('currentBalance').value) || 0;
            const currentRate = parseFloat(document.getElementById('currentRate').value) || 0;
            const remainingYears = parseFloat(document.getElementById('remainingYears').value) || 0;
            const renovationBudget = parseFloat(document.getElementById('renovationBudget').value) || 0;
            const income = parseFloat(document.getElementById('income').value) || 0;

            if (currentBalance === 0 || currentRate === 0 || remainingYears === 0) {
                alert('必要な項目を入力してください');
                return;
            }

            // 簡易計算
            const newRate = Math.max(0.5, currentRate - 0.7);
            const currentMonthlyPayment = calculateMonthlyPayment(currentBalance * 10000, currentRate / 100, remainingYears * 12);
            const renovationMonthlyPayment = calculateMonthlyPayment(renovationBudget * 10000, newRate / 100, remainingYears * 12);
            const newTotalMonthlyPayment = calculateMonthlyPayment((currentBalance + renovationBudget) * 10000, newRate / 100, remainingYears * 12);
            const monthlySavings = Math.max(0, currentMonthlyPayment - (newTotalMonthlyPayment - renovationMonthlyPayment));
            const totalSavings = monthlySavings * remainingYears * 12;

            document.getElementById('newRate').textContent = newRate.toFixed(1) + '%';
