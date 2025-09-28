<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SK Magic Top 1 Zareena - Penapis Air & Udara Terbaik Malaysia</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            box-sizing: border-box;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #ff6b35 0%, #f7931e 50%, #dc2626 100%);
        }
        
        .product-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .floating-animation {
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        
        .pulse-button {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
    </style>
</head>
<body class="font-sans">
    <!-- Header -->
    <header class="gradient-bg text-white py-6 shadow-lg">
        <div class="container mx-auto px-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-4">
                    <div class="w-12 h-12 bg-white rounded-full flex items-center justify-center">
                        <span class="text-orange-500 font-bold text-xl">SK</span>
                    </div>
                    <div>
                        <h1 class="text-2xl md:text-3xl font-bold">SK Magic Top 1 Zareena</h1>
                        <p class="text-orange-100">Penapis Air & Udara Terbaik Malaysia</p>
                    </div>
                </div>
                <nav class="hidden md:flex space-x-6">
                    <a href="#home" class="hover:text-orange-200 transition-colors">Utama</a>
                    <a href="#products" class="hover:text-orange-200 transition-colors">Produk</a>
                    <a href="#contact" class="hover:text-orange-200 transition-colors">Hubungi</a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <div class="floating-animation">
                <h2 class="text-4xl md:text-6xl font-bold mb-6">
                    🌟 SK Magic Malaysia 🌟
                </h2>
                <p class="text-xl md:text-2xl mb-8 text-orange-100">
                    Teknologi Korea Terdepan untuk Air & Udara Bersih
                </p>
                <button onclick="scrollToProducts()" class="pulse-button bg-white text-orange-600 px-8 py-4 rounded-full text-lg font-semibold hover:bg-orange-50 transition-colors shadow-lg">
                    Lihat Produk Kami
                </button>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 bg-gradient-to-br from-orange-50 to-red-50">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-4 text-gray-800">Produk Unggulan Kami</h2>
            <p class="text-center text-gray-600 mb-16 text-lg">Teknologi Korea untuk kehidupan yang lebih sehat</p>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- WIZ V Product -->
                <div class="product-card bg-white rounded-2xl shadow-lg overflow-hidden">
                    <div class="h-64 bg-gradient-to-br from-orange-400 to-red-500 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?w=300&h=200&fit=crop" 
                             alt="SK Magic WIZ V Water Purifier" 
                             class="w-48 h-48 object-contain rounded-lg"
                             onerror="this.src=''; this.style.display='none'; this.nextElementSibling.style.display='block';">
                        <div style="display:none;" class="text-white text-center">
                            <div class="text-6xl mb-4">💧</div>
                            <h3 class="text-2xl font-bold">WIZ V</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-2xl font-bold text-gray-800 mb-3">SK Magic WIZ V</h3>
                        <p class="text-gray-600 mb-4">Penapis air canggih dengan teknologi RO 7-tahap yang menghasilkan air alkali berkualiti tinggi untuk kesihatan keluarga.</p>
                        <ul class="text-sm text-gray-600 mb-6 space-y-2">
                            <li>✅ Teknologi RO 7-Tahap</li>
                            <li>✅ Air Alkali pH 8.5-9.5</li>
                            <li>✅ Kapasiti 11.5L/jam</li>
                            <li>✅ Smart Display</li>
                        </ul>
                        <button onclick="showProductDetails('WIZ V')" class="w-full bg-gradient-to-r from-orange-500 to-red-500 text-white py-3 rounded-lg font-semibold hover:from-orange-600 hover:to-red-600 transition-all">
                            Maklumat Lanjut
                        </button>
                    </div>
                </div>

                <!-- WIZ C Plus Product -->
                <div class="product-card bg-white rounded-2xl shadow-lg overflow-hidden">
                    <div class="h-64 bg-gradient-to-br from-red-400 to-orange-500 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=300&h=200&fit=crop" 
                             alt="SK Magic WIZ C Plus Water Purifier" 
                             class="w-48 h-48 object-contain rounded-lg"
                             onerror="this.src=''; this.style.display='none'; this.nextElementSibling.style.display='block';">
                        <div style="display:none;" class="text-white text-center">
                            <div class="text-6xl mb-4">🚰</div>
                            <h3 class="text-2xl font-bold">WIZ C Plus</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-2xl font-bold text-gray-800 mb-3">SK Magic WIZ C Plus</h3>
                        <p class="text-gray-600 mb-4">Penapis air premium dengan sistem penyejukan dan pemanasan automatik, sesuai untuk pejabat dan rumah.</p>
                        <ul class="text-sm text-gray-600 mb-6 space-y-2">
                            <li>✅ Air Sejuk & Panas</li>
                            <li>✅ Teknologi UV Sterilization</li>
                            <li>✅ Kapasiti Tangki 7L</li>
                            <li>✅ Child Safety Lock</li>
                        </ul>
                        <button onclick="showProductDetails('WIZ C Plus')" class="w-full bg-gradient-to-r from-red-500 to-orange-500 text-white py-3 rounded-lg font-semibold hover:from-red-600 hover:to-orange-600 transition-all">
                            Maklumat Lanjut
                        </button>
                    </div>
                </div>

                <!-- Jiksoo Rich Product -->
                <div class="product-card bg-white rounded-2xl shadow-lg overflow-hidden">
                    <div class="h-64 bg-gradient-to-br from-orange-500 to-red-400 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1585771724684-38269d6639fd?w=300&h=200&fit=crop" 
                             alt="SK Magic Jiksoo Rich Air Purifier" 
                             class="w-48 h-48 object-contain rounded-lg"
                             onerror="this.src=''; this.style.display='none'; this.nextElementSibling.style.display='block';">
                        <div style="display:none;" class="text-white text-center">
                            <div class="text-6xl mb-4">🌪️</div>
                            <h3 class="text-2xl font-bold">Jiksoo Rich</h3>
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-2xl font-bold text-gray-800 mb-3">SK Magic Jiksoo Rich</h3>
                        <p class="text-gray-600 mb-4">Penapis udara pintar dengan teknologi HEPA dan ion negatif untuk udara bersih dan segar sepanjang masa.</p>
                        <ul class="text-sm text-gray-600 mb-6 space-y-2">
                            <li>✅ HEPA Filter H13</li>
                            <li>✅ Ion Negatif Generator</li>
                            <li>✅ Smart Air Quality Sensor</li>
                            <li>✅ Coverage 50m²</li>
                        </ul>
                        <button onclick="showProductDetails('Jiksoo Rich')" class="w-full bg-gradient-to-r from-orange-500 to-red-500 text-white py-3 rounded-lg font-semibold hover:from-orange-600 hover:to-red-600 transition-all">
                            Maklumat Lanjut
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="py-20 gradient-bg text-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-16">Mengapa Pilih SK Magic?</h2>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="text-5xl mb-4">🏆</div>
                    <h3 class="text-xl font-semibold mb-2">Top 1 Malaysia</h3>
                    <p class="text-orange-100">Jenama penapis air & udara #1 di Malaysia</p>
                </div>
                <div class="text-center">
                    <div class="text-5xl mb-4">🇰🇷</div>
                    <h3 class="text-xl font-semibold mb-2">Teknologi Korea</h3>
                    <p class="text-orange-100">Inovasi terdepan dari Korea Selatan</p>
                </div>
                <div class="text-center">
                    <div class="text-5xl mb-4">🛡️</div>
                    <h3 class="text-xl font-semibold mb-2">Jaminan Kualiti</h3>
                    <p class="text-orange-100">Waranti penuh dan servis terbaik</p>
                </div>
                <div class="text-center">
                    <div class="text-5xl mb-4">👨‍👩‍👧‍👦</div>
                    <h3 class="text-xl font-semibold mb-2">Untuk Keluarga</h3>
                    <p class="text-orange-100">Kesihatan keluarga adalah keutamaan</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-4 text-gray-800">Hubungi Zareena</h2>
            <p class="text-center text-gray-600 mb-12 text-lg">Ejen Top 1 SK Magic Malaysia</p>
            
            <div class="max-w-4xl mx-auto grid md:grid-cols-2 gap-12">
                <div class="bg-white p-8 rounded-2xl shadow-lg">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">Maklumat Hubungan</h3>
                    <div class="space-y-4">
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center">
                                <span class="text-white text-xl">📱</span>
                            </div>
                            <div>
                                <p class="font-semibold text-gray-800">WhatsApp</p>
                                <p class="text-gray-600">+60 12-345 6789</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center">
                                <span class="text-white text-xl">✉️</span>
                            </div>
                            <div>
                                <p class="font-semibold text-gray-800">Email</p>
                                <p class="text-gray-600">zareena@skmagic.com.my</p>
                            </div>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center">
                                <span class="text-white text-xl">📍</span>
                            </div>
                            <div>
                                <p class="font-semibold text-gray-800">Lokasi</p>
                                <p class="text-gray-600">Seluruh Malaysia</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white p-8 rounded-2xl shadow-lg">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">Dapatkan Konsultasi Percuma</h3>
                    <form onsubmit="handleContactForm(event)" class="space-y-4">
                        <input type="text" placeholder="Nama Anda" required class="w-full p-4 border border-gray-300 rounded-lg focus:border-orange-500 focus:outline-none">
                        <input type="tel" placeholder="Nombor Telefon" required class="w-full p-4 border border-gray-300 rounded-lg focus:border-orange-500 focus:outline-none">
                        <select required class="w-full p-4 border border-gray-300 rounded-lg focus:border-orange-500 focus:outline-none">
                            <option value="">Pilih Produk Minat</option>
                            <option value="wiz-v">SK Magic WIZ V</option>
                            <option value="wiz-c-plus">SK Magic WIZ C Plus</option>
                            <option value="jiksoo-rich">SK Magic Jiksoo Rich</option>
                            <option value="all">Semua Produk</option>
                        </select>
                        <textarea placeholder="Mesej (pilihan)" rows="4" class="w-full p-4 border border-gray-300 rounded-lg focus:border-orange-500 focus:outline-none"></textarea>
                        <button type="submit" class="w-full bg-gradient-to-r from-orange-500 to-red-500 text-white py-4 rounded-lg font-semibold hover:from-orange-600 hover:to-red-600 transition-all">
                            Hantar Mesej
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="gradient-bg text-white py-12">
        <div class="container mx-auto px-4 text-center">
            <div class="mb-8">
                <h3 class="text-2xl font-bold mb-2">SK Magic Top 1 Zareena</h3>
                <p class="text-orange-100">Ejen Terbaik SK Magic Malaysia</p>
            </div>
            <div class="border-t border-orange-300 pt-8">
                <p class="text-orange-100">&copy; 2024 SK Magic Malaysia. Hak Cipta Terpelihara.</p>
            </div>
        </div>
    </footer>

    <!-- Product Details Modal -->
    <div id="productModal" class="fixed inset-0 bg-black bg-opacity-50 hidden items-center justify-center z-50" onclick="closeModal()">
        <div class="bg-white rounded-2xl p-8 max-w-md mx-4" onclick="event.stopPropagation()">
            <div class="text-center">
                <h3 id="modalTitle" class="text-2xl font-bold text-gray-800 mb-4"></h3>
                <p id="modalContent" class="text-gray-600 mb-6"></p>
                <div class="space-y-3">
                    <button onclick="contactWhatsApp()" class="w-full bg-green-500 text-white py-3 rounded-lg font-semibold hover:bg-green-600 transition-colors">
                        WhatsApp Zareena
                    </button>
                    <button onclick="closeModal()" class="w-full bg-gray-300 text-gray-700 py-3 rounded-lg font-semibold hover:bg-gray-400 transition-colors">
                        Tutup
                    </button>
                </div>
            </div>
        </div>
    </div>

    <script>
        function scrollToProducts() {
            document.getElementById('products').scrollIntoView({ behavior: 'smooth' });
        }

        function showProductDetails(product) {
            const modal = document.getElementById('productModal');
            const title = document.getElementById('modalTitle');
            const content = document.getElementById('modalContent');
            
            const productInfo = {
                'WIZ V': {
                    title: 'SK Magic WIZ V',
                    content: 'Penapis air premium dengan teknologi RO 7-tahap yang menghasilkan air alkali berkualiti tinggi. Sesuai untuk keluarga yang mengutamakan kesihatan dengan air bersih dan bernutrisi.'
                },
                'WIZ C Plus': {
                    title: 'SK Magic WIZ C Plus',
                    content: 'Penapis air dengan sistem penyejukan dan pemanasan automatik. Dilengkapi dengan teknologi UV sterilization untuk memastikan air sentiasa bersih dan selamat diminum.'
                },
                'Jiksoo Rich': {
                    title: 'SK Magic Jiksoo Rich',
                    content: 'Penapis udara pintar dengan teknologi HEPA H13 dan ion negatif generator. Mampu membersihkan udara dari debu, bakteria, dan virus untuk udara yang lebih segar dan sihat.'
                }
            };
            
            title.textContent = productInfo[product].title;
            content.textContent = productInfo[product].content;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeModal() {
            const modal = document.getElementById('productModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function contactWhatsApp() {
            const message = encodeURIComponent('Hai Zareena! Saya berminat dengan produk SK Magic. Boleh beri maklumat lanjut?');
            window.open(`https://wa.me/60123456789?text=${message}`, '_blank', 'noopener,noreferrer');
        }

        function handleContactForm(event) {
            event.preventDefault();
            const formData = new FormData(event.target);
            alert('Terima kasih! Zareena akan menghubungi anda tidak lama lagi.');
            event.target.reset();
        }

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth' });
                }
            });
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98624b5a278a310b',t:'MTc1OTA1MjU4NC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
