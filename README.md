<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>株式会社ベストリンクス - 住宅ローン借り替えでお得にリノベーション</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        .bg-gradient-custom {
            background: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%);
        }
        .text-gradient {
            background: linear-gradient(135deg, #2563eb, #1d4ed8);
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
            box-shadow: 0 8px 20px -3px rgba(37, 99, 235, 0.2);
        }
        .result-card {
            background: linear-gradient(135deg, #3b82f6, #2563eb);
            color: white;
        }
        .savings-highlight {
            background: linear-gradient(135deg, #10b981, #059669);
            color: white;
        }
    </style>
</head>
<body class="bg-gradient-custom min-h-screen">
    <!-- Header -->
    <header class="bg-white shadow-sm border-b border-gray-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <div class="text-2xl font-bold text-gradient">株式会社ベストリンクス</div>
                </div>
                <div class="hidden md:flex space-x-6">
                    <a href="#simulation" class="text-gray-600 hover:text-blue-600 transition-colors">シミュレーション</a>
                    <a href="#benefits" class="text-gray-600 hover:text-blue-600 transition-colors">メリット</a>
                    <a href="#faq" class="text-gray-600 hover:text-blue-600 transition-colors">よくある質問</a>
                    <a href="#contact" class="text-gray-600 hover:text-blue-600 transition-colors">お問い合わせ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-gradient-to-br from-blue-50 to-indigo-100 py-16 px-4">
        <div class="max-w-7xl mx-auto text-center">
            <div class="mb-6">
                <span class="inline-block bg-blue-600 text-white px-4 py-2 rounded-full text-sm font-semibold mb-4">
                    <i class="fas fa-calculator mr-2"></i>借り替えシミュレーション無料
                </span>
            </div>
            <h1 class="text-4xl md:text-6xl font-bold text-gray-900 mb-6">
                住宅ローン借り替えで<br>
                <span class="text-gradient">お得にリノベーション！</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-600 mb-8 max-w-4xl mx-auto">
                現在のローン金利が高いなら、借り替えで月々の支払いを軽減。<br>
                その差額でリノベーション資金を確保しませんか？
            </p>
            <div class="bg-white rounded-lg shadow-custom p-6 max-w-md mx-auto">
                <div class="text-3xl font-bold text-blue-600 mb-2">最大月々</div>
                <div class="text-5xl font-bold text-gray-900 mb-2">5万円</div>
                <div class="text-lg text-gray-600">の支払い軽減が可能！</div>
            </div>
        </div>
    </section>

    <!-- Simulation Section -->
    <section id="simulation" class="py-16 px-4 bg-white">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-calculator text-blue-600 mr-3"></i>
                    借り替えシミュレーション
                </h2>
                <p class="text-xl text-gray-600">現在のローン情報を入力して、借り替え効果を確認してみましょう</p>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- Calculator Input -->
                <div class="bg-gray-50 rounded-xl p-6 shadow-custom">
                    <h3 class="text-2xl font-bold text-gray-900 mb-6">現在のローン情報</h3>
                    <div class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">現在のローン残高（万円）</label>
                            <input type="number" id="currentBalance" placeholder="例: 2500" 
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">現在の金利（%）</label>
                            <input type="number" id="currentRate" placeholder="例: 1.5" step="0.1"
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">残り返済期間（年）</label>
                            <input type="number" id="remainingYears" placeholder="例: 25"
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold text-gray-700 mb-2">借り替え後の金利（%）</label>
                            <input type="number" id="newRate" placeholder="例: 0.8" step="0.1"
                                   class="calculator-input w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <button onclick="calculateSavings()" 
                                class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 px-6 rounded-lg transition-all duration-300 transform hover:scale-105">
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
                            </div>
                        </div>

                        <div class="bg-yellow-50 border border-yellow-200 rounded-xl p-6">
                            <h4 class="text-xl font-bold text-yellow-800 mb-3">
                                <i class="fas fa-home mr-2"></i>リノベーション提案
                            </h4>
                            <div id="renovationProposal" class="text-yellow-700"></div>
                        </div>
                    </div>

                    <div id="placeholder" class="bg-gray-100 rounded-xl p-12 text-center">
                        <i class="fas fa-calculator text-6xl text-gray-400 mb-4"></i>
                        <p class="text-gray-500 text-lg">左側のフォームに情報を入力して<br>シミュレーションを実行してください</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section id="benefits" class="py-16 px-4 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">借り替えリノベーションのメリット</h2>
                <p class="text-xl text-gray-600">なぜ今、住宅ローン借り替えが注目されているのか</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white rounded-xl p-8 shadow-custom text-center">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-percent text-2xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">金利差でお得に</h3>
                    <p class="text-gray-600">現在の低金利環境を活用して、月々の支払いを大幅に軽減。その差額をリノベーション資金に活用できます。</p>
                </div>

                <div class="bg-white rounded-xl p-8 shadow-custom text-center">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-home text-2xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">住まいの価値向上</h3>
                    <p class="text-gray-600">リノベーションにより住宅の資産価値が向上。将来の売却時により高い価格での売却が期待できます。</p>
                </div>

                <div class="bg-white rounded-xl p-8 shadow-custom text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fas fa-chart-line text-2xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">税制優遇の活用</h3>
                    <p class="text-gray-600">リノベーションによる税制優遇措置を活用することで、さらなる費用削減効果が期待できます。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="py-16 px-4 bg-white">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">ご利用の流れ</h2>
                <p class="text-xl text-gray-600">簡単3ステップで理想の住まいを実現</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="w-20 h-20 bg-blue-600 text-white rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">1</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">無料相談・シミュレーション</h3>
                    <p class="text-gray-600">現在のローン状況をお聞かせください。専門スタッフが最適な借り替えプランをご提案いたします。</p>
                </div>

                <div class="text-center">
                    <div class="w-20 h-20 bg-blue-600 text-white rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">2</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">借り替え手続き</h3>
                    <p class="text-gray-600">面倒な借り替え手続きは当社がサポート。お客様の負担を最小限に抑えて進行いたします。</p>
                </div>

                <div class="text-center">
                    <div class="w-20 h-20 bg-blue-600 text-white rounded-full flex items-center justify-center mx-auto mb-6 text-2xl font-bold">3</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">リノベーション実施</h3>
                    <p class="text-gray-600">軽減された月々支払い分を活用して、理想のリノベーションを実現。新しい住まいでの生活をスタート。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-16 px-4 bg-gray-50">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-900 mb-4">よくある質問</h2>
                <p class="text-xl text-gray-600">お客様からよくいただくご質問にお答えします</p>
            </div>

            <div class="space-y-6">
                <div class="bg-white rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-blue-600 mr-2"></i>
                        借り替えにはどのくらいの費用がかかりますか？
                    </h3>
                    <p class="text-gray-600">一般的に借り替え費用は借入額の2-3%程度ですが、金利差によるメリットが大きく上回るケースがほとんどです。詳細な費用対効果は無料シミュレーションでご確認いただけます。</p>
                </div>

                <div class="bg-white rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-blue-600 mr-2"></i>
                        借り替えの手続きにはどのくらい時間がかかりますか？
                    </h3>
                    <p class="text-gray-600">審査から実行まで通常1-2ヶ月程度です。当社が手続きをサポートいたしますので、お客様の負担は最小限に抑えられます。</p>
                </div>

                <div class="bg-white rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-blue-600 mr-2"></i>
                        リノベーション費用はどのように調達しますか？
                    </h3>
                    <p class="text-gray-600">借り替えによる月々支払い軽減分を積み立てる方法や、リフォームローンとの組み合わせなど、お客様のご希望に応じて最適な方法をご提案いたします。</p>
                </div>

                <div class="bg-white rounded-xl p-6 shadow-custom">
                    <h3 class="text-lg font-bold text-gray-900 mb-3">
                        <i class="fas fa-question-circle text-blue-600 mr-2"></i>
                        相談は無料ですか？
                    </h3>
                    <p class="text-gray-600">はい、初回相談およびシミュレーションは完全無料です。お客様に最適なプランが見つかってからご契約いただく形になります。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 px-4 bg-blue-600">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-4xl font-bold text-white mb-4">今すぐ無料相談を始める</h2>
            <p class="text-xl text-blue-100 mb-8">専門スタッフがあなたの住宅ローン借り替えをサポートします</p>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-white rounded-xl p-6 text-center">
                    <i class="fas fa-phone text-3xl text-blue-600 mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">お電話でのご相談</h3>
                    <div class="text-2xl font-bold text-blue-600 mb-2">0120-123-456</div>
                    <p class="text-gray-600">平日 9:00-18:00<br>土日祝 10:00-17:00</p>
                </div>

                <div class="bg-white rounded-xl p-6 text-center">
                    <i class="fas fa-envelope text-3xl text-blue-600 mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">メールでのご相談</h3>
                    <button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg transition-colors">
                        お問い合わせフォーム
                    </button>
                    <p class="text-gray-600 mt-2">24時間受付<br>2営業日以内にご返信</p>
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
                    <p class="text-gray-400 mb-4">住宅ローンの専門家として、お客様の最適な住宅資金計画をサポートいたします。</p>
                    <div class="flex space-x-4">
                        <i class="fab fa-facebook text-2xl text-gray-400 hover:text-white cursor-pointer"></i>
                        <i class="fab fa-twitter text-2xl text-gray-400 hover:text-white cursor-pointer"></i>
                        <i class="fab fa-linkedin text-2xl text-gray-400 hover:text-white cursor-pointer"></i>
                    </div>
                </div>

                <div>
                    <h4 class="text-lg font-bold mb-4">サービス</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">住宅ローン借り替え</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">リノベーション相談</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">資金計画サポート</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">税制優遇相談</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="text-lg font-bold mb-4">会社情報</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li>〒100-0001</li>
                        <li>東京都千代田区千代田1-1-1</li>
                        <li>TEL: 0120-123-456</li>
                        <li>営業時間: 平日 9:00-18:00</li>
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
            const currentBalance = parseFloat(document.getElementById('currentBalance').value);
            const currentRate = parseFloat(document.getElementById('currentRate').value) / 100;
            const remainingYears = parseFloat(document.getElementById('remainingYears').value);
            const newRate = parseFloat(document.getElementById('newRate').value) / 100;

            // Validate inputs
            if (!currentBalance || !currentRate || !remainingYears || !newRate) {
                alert('すべての項目を入力してください。');
                return;
            }

            if (newRate >= currentRate) {
                alert('借り替え後の金利は現在の金利より低い値を入力してください。');
                return;
            }

            // Calculate monthly payments
            const monthlyCurrentRate = currentRate / 12;
            const monthlyNewRate = newRate / 12;
            const totalMonths = remainingYears * 12;
            const balanceInYen = currentBalance * 10000;

            // Current monthly payment calculation
            const currentPayment = (balanceInYen * monthlyCurrentRate * Math.pow(1 + monthlyCurrentRate, totalMonths)) / 
                                 (Math.pow(1 + monthlyCurrentRate, totalMonths) - 1);

            // New monthly payment calculation
            const newPayment = (balanceInYen * monthlyNewRate * Math.pow(1 + monthlyNewRate, totalMonths)) / 
                             (Math.pow(1 + monthlyNewRate, totalMonths) - 1);

            // Calculate savings
            const monthlySavings = currentPayment - newPayment;
            const yearlySavings = monthlySavings * 12;

            // Display results
            document.getElementById('currentPayment').textContent = `¥${Math.round(currentPayment).toLocaleString()}`;
            document.getElementById('newPayment').textContent = `¥${Math.round(newPayment).toLocaleString()}`;
            document.getElementById('monthlySavings').textContent = `¥${Math.round(monthlySavings).toLocaleString()}`;
            document.getElementById('yearlySavings').textContent = `¥${Math.round(yearlySavings).toLocaleString()}`;

            // Generate renovation proposal
            let renovationProposal = '';
            const monthlySavingsAmount = Math.round(monthlySavings);
            
            if (monthlySavingsAmount >= 30000) {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の軽減で、3年間で約${Math.round(yearlySavings * 3 / 10000)}万円のリノベーション資金を確保可能！キッチン・バス・トイレの水回り全面改修や間取り変更も実現できます。`;
            } else if (monthlySavingsAmount >= 20000) {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の軽減で、2年間で約${Math.round(yearlySavings * 2 / 10000)}万円のリノベーション資金を確保可能！水回り設備の更新や内装の全面リフォームが可能です。`;
            } else if (monthlySavingsAmount >= 10000) {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の軽減で、部分的なリノベーションから始めませんか？キッチンやバスルームの設備更新、壁紙・フローリングの張替えなどが可能です。`;
            } else {
                renovationProposal = `月々${Math.round(monthlySavings / 1000)}万円の軽減でも、長期的に見れば大きな効果があります。設備の部分交換や省エネリフォームから始めることをおすすめします。`;
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
        });
    </script>
</body>
</html>
