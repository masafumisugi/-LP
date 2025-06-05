<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>株式会社ベストリンクス - このサイト限定！実質無料でリノベができる！？</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        .bg-gradient-custom {
            background: linear-gradient(135deg, #fff7ed 0%, #fed7aa 100%);
        }
        .text-gradient {
            background: linear-gradient(135deg, #ea580c, #dc2626);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        .shadow-custom {
            box-shadow: 0 10px 25px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .calculator-input {
            transition: all 0.3s ease;
        }
        .calculator-input:focus {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px -3px rgba(234, 88, 12, 0.2);
        }
        .result-card {
            background: linear-gradient(135deg, #ea580c, #dc2626);
            color: white;
        }
        .savings-highlight {
            background: linear-gradient(135deg, #f97316, #ea580c);
            color: white;
        }
        .hero-gradient {
            background: linear-gradient(135deg, #fff7ed 0%, #fed7aa 50%, #fb923c 100%);
        }
        .orange-600 {
            color: #ea580c;
        }
        .bg-orange-600 {
            background-color: #ea580c;
        }
        .bg-orange-700 {
            background-color: #c2410c;
        }
        .hover\:bg-orange-700:hover {
            background-color: #c2410c;
        }
        .text-orange-600 {
            color: #ea580c;
        }
        .border-orange-500 {
            border-color: #f97316;
        }
        .focus\:ring-orange-500:focus {
            --tw-ring-color: #f97316;
        }
        .limited-offer {
            animation: pulse 2s infinite;
            background: linear-gradient(45deg, #ef4444, #f97316);
            color: white;
        }
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.8; }
        }
        .special-rate-highlight {
            background: linear-gradient(135deg, #10b981, #059669);
            color: white;
            border: 3px solid #34d399;
        }
    </style>
</head>
<body class="bg-gradient-custom min-h-screen">
    <!-- Header -->
    <header class="bg-white shadow-sm border-b border-orange-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <div class="text-2xl font-bold text-gradient">株式会社ベストリンクス</div>
                    <div class="ml-4 text-sm text-gray-600 hidden md:block">大阪府知事許可（特-5）第155156号</div>
                </div>
                <div class="hidden md:flex space-x-6">
                    <a href="#simulation" class="text-gray-600 hover:text-orange-600 transition-colors">シミュレーション</a>
                    <a href="#benefits" class="text-gray-600 hover:text-orange-600 transition-colors">メリット</a>
                    <a href="#faq" class="text-gray-600 hover:text-orange-600 transition-colors">よくある質問</a>
                    <a href="#contact" class="text-gray-600 hover:text-orange-600 transition-colors">お問い合わせ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative hero-gradient py-16 px-4">
        <div class="max-w-7xl mx-auto text-center">
            <div class="mb-6">
                <span class="limited-offer inline-block px-6 py-3 rounded-full text-lg font-bold mb-4">
                    <i class="fas fa-star mr-2"></i>このサイトを見た方限定！
                </span>
                <br>
                <span class="inline-block bg-orange-600 text-white px-4 py-2 rounded-full text-sm font-semibold mb-4">
                    <i class="fas fa-calculator mr-2"></i>借り替えシミュレーション無料
                </span>
                <span class="inline-block bg-green-600 text-white px-4 py-2 rounded-full text-sm font-semibold mb-4 ml-2">
                    <i class="fas fa-percent mr-2"></i>特別金利適用
                </span>
            </div>
            <h1 class="text-4xl md:text-6xl font-bold text-gray-900 mb-6">
                <span class="text-gradient">実質無料で</span><br>
                リノベができる！？
            </h1>
            <p class="text-xl md:text-2xl text-gray-700 mb-8 max-w-4xl mx-auto">
                住宅ローン借り替えで月々の支払いを軽減。<br>
                <span class="font-bold text-orange-700">その差額でリノベーション費用を賄えば実質無料！</span><br>
                <span class="text-green-700 font-bold">特別金利適用で大幅軽減を実現</span>
            </p>
            <div class="bg-white rounded-lg shadow-custom p-6 max-w-md mx-auto border-4 border-orange-300">
                <div class="text-orange-600 text-lg font-bold mb-2">🏠 月々の支払い軽減で</div>
                <div class="text-4xl font-bold text-gray-900 mb-2">実質無料</div>
                <div class="text-lg text-gray-600">リノベーション！</div>
                <div class="mt-3 text-sm text-green-700 font-bold">※特別金利適用で最大月々5万円の軽減効果</div>
            </div>
            <div class="mt-6 text-sm text-gray-600">
                大阪・兵庫・奈良・京都エリア対応
            </div>
        </div>
    </section>

    <!-- Simulation Section -->
    <section id="simulation" class="py-16 px-4 bg-white">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-calculator text-orange-600 mr-3"></i>
                    借り替えシミュレーション
                </h2>
                <p class="text-xl text-gray-600">現在のローン情報を入力して、特別金利での借り替え効果を確認してみましょう</p>
                <div class="mt-4 inline-block special-rate-highlight px-6 py-3 rounded-lg">
                    <i class="fas fa-star mr-2"></i>
                    <strong>サイト限定特別金利での借り替えが可能！</strong>
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- Calculator Input -->
                <div class="bg-orange-50 rounded-xl p-6 shadow-custom">
                    <h3 class="text-2xl font-bold text-gray-900 mb-6">現在のローン情報</h3>
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">最初に借りた金額（万円）</label>
                            <input type="number" id="originalAmount" placeholder="例: 4000" 
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-orange-500 focus:border-orange-500">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">最初に借りた時の金利（%）</label>
                            <input type="number" id="originalRate" placeholder="例: 1.8" step="0.01"
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-orange-500 focus:border-orange-500">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">最初に借りた期間（年）</label>
                            <input type="number" id="originalTerm" placeholder="例: 35" 
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-orange-500 focus:border-orange-500">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">現在のローン残高（万円）</label>
                            <input type="number" id="currentBalance" placeholder="例: 2500" 
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-orange-500 focus:border-orange-500">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">残り返済期間（年）</label>
                            <input type="number" id="remainingYears" placeholder="例: 25"
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-orange-500 focus:border-orange-500">
                        </div>
                        <button onclick="calculateSavings()" 
                                class="w-full bg-orange-600 hover:bg-orange-700 text-white font-bold py-4 px-6 rounded-lg transition-all duration-300 transform hover:scale-105">
                            <i class="fas fa-calculator mr-2"></i>シミュレーション実行
                        </button>
                    </div>
                </div>

                <!-- Results -->
                <div class="space-y-6">
                    <div id="results" class="hidden">
                        <div class="result-card rounded-xl p-6 shadow-custom mb-6">
                            <h3 class="text-2xl font-bold mb-4">
                                <i class="fas fa-chart-line mr-2"></i>シミュレーション結果
                            </h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div class="bg-white bg-opacity-20 rounded-lg p-4">
                                    <div class="text-sm opacity-90">現在の月々支払い</div>
                                    <div id="currentPayment" class="text-2xl font-bold">-</div>
                                </div>
                                <div class="bg-white bg-opacity-20 rounded-lg p-4">
                                    <div class="text-sm opacity-90">借り替え後の月々支払い</div>
                                    <div id="newPayment" class="text-2xl font-bold">-</div>
                                </div>
                            </div>
                        </div>

                        <div class="savings-highlight rounded-xl p-6 shadow-custom mb-6">
                            <h3 class="text-2xl font-bold mb-4">
                                <i class="fas fa-piggy-bank mr-2"></i>借り替え効果
                            </h3>
                            <div class="text-center">
                                <div class="text-sm opacity-90">月々の軽減額</div>
                                <div id="monthlySavings" class="text-4xl font-bold mb-2">-</div>
                                <div class="text-sm opacity-90">年間軽減額</div>
                                <div id="yearlySavings" class="text-2xl font-bold">-</div>
                                <div class="text-sm opacity-90 mt-2">総軽減額（全期間）</div>
                                <div id="totalSavings" class="text-xl font-bold">-</div>
                            </div>
                        </div>

                        <div class="bg-yellow-50 border border-yellow-200 rounded-xl p-6">
                            <h4 class="text-xl font-bold text-yellow-800 mb-3">
                                <i class="fas fa-home mr-2"></i>実質無料リノベーション提案
                            </h4>
                            <div id="renovationProposal" class="text-yellow-700"></div>
                        </div>
                    </div>

                    <div id="placeholder" class="bg-gray-100 rounded-xl p-12 text-center">
                        <i class="fas fa-calculator text-6xl text-gray-400 mb-4"></i>
                        <p class="text-gray-500 text-lg">左側のフォームに情報を入力して<br>シミュレーションを実行してください</p>
                        <p class="text-green-600 font-bold mt-2">特別金利での計算を行います</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section id="benefits" class="py-16 px-4 bg-orange-50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">実質無料リノベーションのメリット</h2>
                <p class="text-xl text-gray-600">なぜ今、住宅ローン借り替えが注目されているのか</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white rounded-xl p-8 shadow-custom text-center">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-percent text-2xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">特別金利で大幅軽減</h3>
                    <p class="text-gray-600">通常の借り替え金利より更に低い特別金利を適用。月々の支払いを大幅に軽減し、その差額をリノベーション資金に活用できます。</p>
                </div>

                <div class="bg-white rounded-xl p-8 shadow-custom text-center">
                    <div class="w-16 h-16 bg-orange-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-home text-2xl text-orange-600"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">建設業許可の確かな技術</h3>
                    <p class="text-gray-600">大阪府知事許可を持つ確かな技術力でリノベーションを実施。住宅の資産価値向上と将来の売却時の高い評価を実現します。</p>
                </div>

                <div class="bg-white rounded-xl p-8 shadow-custom text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-chart-line text-2xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">実質負担ゼロ</h3>
                    <p class="text-gray-600">借り替えによる支払い軽減額でリノベーション費用を賄うため、実質的な追加負担なしで理想の住まいを実現できます。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Company Strength Section -->
    <section class="py-16 px-4 bg-white">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">ベストリンクスの強み</h2>
                <p class="text-xl text-gray-600">関西エリアでの豊富な実績と確かな技術力</p>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-orange-50 rounded-xl p-8">
                    <h3 class="text-2xl font-bold text-gray-900 mb-4">
                        <i class="fas fa-certificate text-orange-600 mr-3"></i>
                        建設業許可取得の安心感
                    </h3>
                    <p class="text-gray-600 mb-4">大阪府知事許可（特-5）第155156号を取得。法令に基づいた適正な施工で、お客様に安心をお届けします。</p>
                    <ul class="text-gray-600 space-y-2">
                        <li><i class="fas fa-check text-green-600 mr-2"></i>建築一式工事対応</li>
                        <li><i class="fas fa-check text-green-600 mr-2"></i>リフォーム・リノベーション専門</li>
                        <li><i class="fas fa-check text-green-600 mr-2"></i>各種リペア補修技術</li>
                    </ul>
                </div>

                <div class="bg-green-50 rounded-xl p-8">
                    <h3 class="text-2xl font-bold text-gray-900 mb-4">
                        <i class="fas fa-map-marker-alt text-green-600 mr-3"></i>
                        関西エリア密着対応
                    </h3>
                    <p class="text-gray-600 mb-4">大阪市・神戸市を中心に、大阪・兵庫・奈良・京都の関西一円でサービスを展開。地域密着だからこその迅速な対応が可能です。</p>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="text-center">
                            <div class="text-2xl font-bold text-green-600">大阪市</div>
                            <div class="text-sm text-gray-600">東淀川区に本社</div>
                        </div>
                        <div class="text-center">
                            <div class="text-2xl font-bold text-green-600">関西一円</div>
                            <div class="text-sm text-gray-600">迅速対応可能</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="py-16 px-4 bg-orange-50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">ご利用の流れ</h2>
                <p class="text-xl text-gray-600">簡単3ステップで実質無料リノベーションを実現</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="w-20 h-20 bg-orange-600 text-white rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">1</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">無料相談・シミュレーション</h3>
                    <p class="text-gray-600">現在のローン状況をお聞かせください。専門スタッフが特別金利での最適な借り替えプランをご提案いたします。</p>
                </div>

                <div class="text-center">
                    <div class="w-20 h-20 bg-orange-600 text-white rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">2</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">借り替え手続き</h3>
                    <p class="text-gray-600">面倒な借り替え手続きは当社がサポート。特別金利での借り替えをお客様の負担を最小限に抑えて進行いたします。</p>
                </div>

                <div class="text-center">
                    <div class="w-20 h-20 bg-orange-600 text-white rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">3</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">実質無料リノベーション実施</h3>
                    <p class="text-gray-600">軽減された月々支払い分を活用して、理想のリノベーションを実現。実質負担なしで新しい住まいでの生活をスタート。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-16 px-4 bg-white">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">よくある質問</h2>
                <p class="text-xl text-gray-600">お客様からよくいただくご質問にお答えします</p>
            </div>

            <div class="space-y-6">
                <div class="bg-orange-50 rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-orange-600 mr-2"></i>
                        特別金利は本当に適用されるのですか？
                    </h3>
                    <p class="text-gray-600">はい。このサイトをご覧の方限定で特別金利での借り替えが可能です。審査に通過したお客様には確実に適用いたします。通常の借り替え金利より更に低い金利での借り替えを実現しています。</p>
                </div>

                <div class="bg-orange-50 rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-orange-600 mr-2"></i>
                        本当に実質無料でリノベーションできるのですか？
                    </h3>
                    <p class="text-gray-600">はい。特別金利での住宅ローン借り替えによる月々の支払い軽減額をリノベーション費用に充てることで、実質的な追加負担なしでリノベーションが可能です。シミュレーションで具体的な効果をご確認いただけます。</p>
                </div>

                <div class="bg-orange-50 rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-orange-600 mr-2"></i>
                        借り替えにはどのくらいの費用がかかりますか？
                    </h3>
                    <p class="text-gray-600">一般的に借り替え費用は借入額の2-3%程度ですが、特別金利による大幅な金利差メリットが費用を大きく上回るケースがほとんどです。詳細な費用対効果は無料シミュレーションでご確認いただけます。</p>
                </div>

                <div class="bg-orange-50 rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-orange-600 mr-2"></i>
                        借り替えの手続きにはどのくらい時間がかかりますか？
                    </h3>
                    <p class="text-gray-600">審査から実行まで通常1-2ヶ月程度です。当社が手続きをサポートいたしますので、お客様の負担は最小限に抑えられます。特別金利の適用についても責任を持ってサポートいたします。</p>
                </div>

                <div class="bg-orange-50 rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-orange-600 mr-2"></i>
                        相談は無料ですか？
                    </h3>
                    <p class="text-gray-600">はい、初回相談およびシミュレーションは完全無料です。特別金利での借り替え効果を詳しくご説明し、お客様に最適なプランが見つかってからご契約いただく形になります。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 px-4 bg-orange-600">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-4xl font-bold text-white mb-4">今すぐ無料相談を始める</h2>
            <p class="text-xl text-orange-100 mb-8">専門スタッフがあなたの実質無料リノベーションをサポートします</p>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-white rounded-xl p-6 text-center">
                    <i class="fas fa-phone text-3xl text-orange-600 mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">お電話でのご相談</h3>
                    <div class="text-2xl font-bold text-orange-600 mb-2">06-6657-5092</div>
                    <p class="text-gray-600">営業時間 9:00-19:00<br>年中無休（年末年始除く）</p>
                </div>

                <div class="bg-white rounded-xl p-6 text-center">
                    <i class="fas fa-envelope text-3xl text-orange-600 mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">メールでのご相談</h3>
                    <button class="bg-orange-600 hover:bg-orange-700 text-white font-bold py-3 px-6 rounded-lg transition-colors">
                        お問い合わせフォーム
                    </button>
                    <p class="text-gray-600 mt-2">24時間受付<br>2営業日以内にご返信</p>
                </div>
            </div>

            <div class="mt-8 bg-white bg-opacity-10 rounded-xl p-6">
                <h4 class="text-xl font-bold text-white mb-4">会社情報</h4>
                <div class="text-orange-100 space-y-2">
                    <p><i class="fas fa-building mr-2"></i>株式会社ベストリンクス</p>
                    <p><i class="fas fa-user mr-2"></i>代表取締役：山本 博士</p>
                    <p><i class="fas fa-map-marker-alt mr-2"></i>〒533-0033 大阪府大阪市東淀川区東中島2-26-10 3F</p>
                    <p><i class="fas fa-certificate mr-2"></i>大阪府知事許可（特-5）第155156号</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12 px-4">
        <div class="max-w-7xl mx-auto">
            <div class="grid md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-2xl font-bold mb-4">株式会社ベストリンクス</h3>
                    <p class="text-gray-400 mb-4">建設業許可を取得した関西の住宅ローン・リノベーション専門会社として、特別金利でのお客様の実質無料リノベーションを実現いたします。</p>
                    <div class="space-y-2 text-gray-400">
                        <p>代表取締役：山本 博士</p>
                        <p>資本金：2,000万円</p>
                        <p>大阪府知事許可（特-5）第155156号</p>
                    </div>
                </div>

                <div>
                    <h4 class="text-lg font-bold mb-4">サービス</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">住宅ローン借り替え（特別金利）</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">リノベーション・リフォーム</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">各種リペア補修</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">資金計画サポート</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">リペアスクール</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-lg font-bold mb-4">対応エリア・お問い合わせ</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><i class="fas fa-map-marker-alt mr-2"></i>大阪市・神戸市中心</li>
                        <li><i class="fas fa-map mr-2"></i>大阪・兵庫・奈良・京都</li>
                        <li><i class="fas fa-phone mr-2"></i>06-6657-5092</li>
                        <li><i class="fas fa-fax mr-2"></i>06-6657-5093</li>
                        <li><i class="fas fa-clock mr-2"></i>営業時間: 9:00-19:00</li>
                    </ul>
                </div>
            </div>

            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2024 株式会社ベストリンクス. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        function calculateSavings() {
            // Get input values
            const originalAmount = parseFloat(document.getElementById('originalAmount').value);
            const originalRate = parseFloat(document.getElementById('originalRate').value) / 100;
            const originalTerm = parseFloat(document.getElementById('originalTerm').value);
            const currentBalance = parseFloat(document.getElementById('currentBalance').value);
            const remainingYears = parseFloat(document.getElementById('remainingYears').value);
            const newRate = 0.007; // Internal rate: 0.7%

            // Validate inputs
            if (!originalAmount || !originalRate || !originalTerm || !currentBalance || !remainingYears) {
                alert('すべての項目を入力してください。');
                return;
            }

            if (originalAmount <= 0 || originalRate <= 0 || originalTerm <= 0 || currentBalance <= 0 || remainingYears <= 0) {
                alert('正の数値を入力してください。');
                return;
            }

            if (currentBalance > originalAmount) {
                alert('現在の残高は最初の借入金額を超えることはできません。');
                return;
            }

            if (remainingYears > originalTerm) {
                alert('残り返済期間は最初の借入期間を超えることはできません。');
                return;
            }

            if (newRate >= originalRate) {
                alert('特別金利は現在の金利より低い場合に適用されます。現在の金利をご確認ください。');
                return;
            }

            // Convert to proper units
            const monthlyOriginalRate = originalRate / 12;
            const monthlyNewRate = newRate / 12;
            const originalTotalMonths = originalTerm * 12;
            const remainingMonths = remainingYears * 12;
            const originalAmountInYen = originalAmount * 10000;
            const balanceInYen = currentBalance * 10000;

            // Calculate current monthly payment (based on original loan terms)
            const currentPayment = (originalAmountInYen * monthlyOriginalRate * Math.pow(1 + monthlyOriginalRate, originalTotalMonths)) / 
                                 (Math.pow(1 + monthlyOriginalRate, originalTotalMonths) - 1);

            // Calculate new monthly payment with special rate (0.7%)
            const newPayment = (balanceInYen * monthlyNewRate * Math.pow(1 + monthlyNewRate, remainingMonths)) / 
                             (Math.pow(1 + monthlyNewRate, remainingMonths) - 1);

            // Calculate savings
            const monthlySavings = currentPayment - newPayment;
            const yearlySavings = monthlySavings * 12;
            const totalSavings = monthlySavings * remainingMonths;

            // Ensure positive savings
            if (monthlySavings <= 0) {
                alert('現在の条件では借り替えメリットが少ないです。専門スタッフにご相談ください。');
                return;
            }

            // Display results
            document.getElementById('currentPayment').textContent = `¥${Math.round(currentPayment).toLocaleString()}`;
            document.getElementById('newPayment').textContent = `¥${Math.round(newPayment).toLocaleString()}`;
            document.getElementById('monthlySavings').textContent = `¥${Math.round(monthlySavings).toLocaleString()}`;
            document.getElementById('yearlySavings').textContent = `¥${Math.round(yearlySavings).toLocaleString()}`;
            document.getElementById('totalSavings').textContent = `¥${Math.round(totalSavings).toLocaleString()}`;

            // Generate renovation proposal
            let renovationProposal = '';
            const monthlySavingsAmount = Math.round(monthlySavings);
            
            if (monthlySavingsAmount >= 50000) {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の大幅軽減！3年間で約${Math.round(yearlySavings * 3 / 10000)}万円のリノベーション資金を確保できます。建設業許可を持つベストリンクスなら、フルリノベーション（キッチン・バス・トイレの水回り全面改修＋間取り変更＋内装全面リニューアル）も安心してお任せください。特別金利の効果で実質負担なしで理想の住まいを実現！`;
            } else if (monthlySavingsAmount >= 30000) {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の軽減で、3年間で約${Math.round(yearlySavings * 3 / 10000)}万円のリノベーション資金を確保！水回り設備の全面更新＋内装リフォームなど、大規模なリノベーションが特別金利の効果で実質負担なしで実現します。確かな技術力で品質の高い工事をお約束いたします。`;
            } else if (monthlySavingsAmount >= 20000) {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の軽減で、2-3年間で約${Math.round(yearlySavings * 2.5 / 10000)}万円のリノベーション資金を確保！キッチンまたはバスルームの設備更新、壁紙・フローリングの全面張替えなど、住まいの快適性を大幅に向上させるリノベーションが特別金利の効果で実質負担なしで可能です。`;
            } else if (monthlySavingsAmount >= 10000) {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の軽減でも、長期的に見れば大きな効果があります。設備の部分更新や省エネリフォーム、各種リペア工事から始めることで、特別金利の恩恵を受けながら実質負担を抑えて住まいの価値を向上させることができます。関西エリア密着のベストリンクスが丁寧にサポートいたします。`;
            } else {
                renovationProposal = `特別金利の効果により月々${Math.round(monthlySavings / 1000)}万円の軽減を実現！小規模なリフォームや設備メンテナンスから始めて、段階的に住まいの改善を進めることが可能です。建設業許可を持つ当社が、お客様のご予算に合わせた最適なプランをご提案いたします。`;
            }

            document.getElementById('renovationProposal').textContent = renovationProposal;

            // Show results and hide placeholder
            document.getElementById('results').classList.remove('hidden');
            document.getElementById('placeholder').classList.add('hidden');

            // Smooth scroll to results
            document.getElementById('results').scrollIntoView({ behavior: 'smooth', block: 'nearest' });
        }

        // Add enter key support for inputs
        document.addEventListener('DOMContentLoaded', function() {
            const inputs = document.querySelectorAll('.calculator-input');
            inputs.forEach(input => {
                input.addEventListener('keypress', function(e) {
                    if (e.key === 'Enter') {
                        calculateSavings();
                    }
                });
            });

            // Set updated placeholders for input guidance
            document.getElementById('originalAmount').placeholder = "例: 4000";
            document.getElementById('originalRate').placeholder = "例: 1.8";
            document.getElementById('originalTerm').placeholder = "例: 35";
            document.getElementById('currentBalance').placeholder = "例: 2500";
            document.getElementById('remainingYears').placeholder = "例: 25";
        });
    </script>
</body>
</html>
