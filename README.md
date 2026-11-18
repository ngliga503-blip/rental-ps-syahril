<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PlayStation Rental Service - Sewa PS Murah & Cepat</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter & Orbitron -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Orbitron:wght@600;800&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        tech: ['Orbitron', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            blue: '#00439C',
                            lightBlue: '#0070D1',
                            accent: '#00F0FF',
                            dark: '#0B0F19',
                            card: '#161F33',
                            cardBorder: '#233253'
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-brand-dark text-slate-100 font-sans antialiased min-h-screen flex flex-col justify-between">

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-50 bg-brand-dark/90 backdrop-blur-md border-b border-brand-cardBorder">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-brand-blue to-brand-accent flex items-center justify-center text-white text-xl shadow-lg shadow-brand-blue/30">
                    <i class="fa-brands fa-playstation"></i>
                </div>
                <span class="font-tech text-2xl font-bold tracking-wider bg-gradient-to-r from-white via-slate-200 to-brand-accent bg-clip-text text-transparent">
                    RENTAL<span class="text-brand-accent">.MAULANA</span>
                </span>
            </div>
            
            <nav class="hidden md:flex space-x-8 text-sm font-semibold tracking-wide">
                <a href="#katalog" class="hover:text-brand-accent transition-colors">Daftar Harga</a>
                <a href="#layanan" class="hover:text-brand-accent transition-colors">Layanan Tipe</a>
                <a href="#order" class="hover:text-brand-accent transition-colors">Pesan Sekarang</a>
                <a href="#pembayaran" class="hover:text-brand-accent transition-colors">Metode Bayar</a>
            </nav>

            <div>
                <a href="#order" class="px-5 py-2.5 rounded-full bg-gradient-to-r from-brand-lightBlue to-brand-blue hover:from-brand-blue hover:to-brand-lightBlue text-white font-semibold text-sm shadow-md hover:shadow-brand-blue/50 transition-all duration-300 flex items-center space-x-2">
                    <i class="fa-brands fa-whatsapp text-lg text-emerald-400"></i>
                    <span>Sewa Sekarang</span>
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative py-16 md:py-24 overflow-hidden border-b border-brand-cardBorder/50">
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-brand-lightBlue/20 rounded-full blur-3xl -z-10 pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <span class="inline-block px-4 py-1.5 rounded-full bg-brand-cardBorder/80 text-brand-accent text-xs font-semibold tracking-widest uppercase mb-4 border border-brand-accent/30">
                Rental PlayStation Terpercaya & Cepat
            </span>
            <h1 class="font-tech text-4xl sm:text-6xl font-extrabold text-white tracking-tight mb-6 leading-tight">
                MAIN GAME FAVORITMU <br class="hidden sm:block"/> TANPA HARUS MEMBELI
            </h1>
            <p class="max-w-2xl mx-auto text-slate-400 text-base sm:text-lg mb-8">
                Sewa PlayStation 4 & PlayStation 5 unit bersih, game update lengkap 2026, dan stik original. Melayani main di tempat rental, COD, atau diantar langsung ke rumah Anda!
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#order" class="px-8 py-3.5 rounded-xl bg-emerald-500 hover:bg-emerald-600 text-white font-bold text-base shadow-lg shadow-emerald-500/25 transition-all flex items-center space-x-3">
                    <i class="fa-brands fa-whatsapp text-xl"></i>
                    <span>Order via WhatsApp</span>
                </a>
                <a href="#katalog" class="px-8 py-3.5 rounded-xl bg-brand-card hover:bg-brand-cardBorder text-slate-200 border border-slate-700 font-semibold text-base transition-all">
                    Lihat Price List
                </a>
            </div>
        </div>
    </section>

    <!-- Fitur Layanan / Bentuk Pemesanan -->
    <section id="layanan" class="py-16 bg-brand-dark/50 border-b border-brand-cardBorder">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="font-tech text-3xl font-bold text-white mb-2">BENTUK PEMESANAN</h2>
                <p class="text-slate-400">Pilih opsi penggunaan unit yang paling nyaman untuk Anda</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Card Main di Tempat -->
                <div class="bg-brand-card p-8 rounded-2xl border border-brand-cardBorder hover:border-brand-accent/50 transition duration-300 relative group">
                    <div class="w-14 h-14 rounded-xl bg-brand-blue/30 text-brand-accent flex items-center justify-center text-2xl mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-gamepad"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Main di Tempat Rental</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Nikmati ruangan ber-AC dingin, TV 4K ukuran besar, sofa nyaman, dan suasana seru bermain bersama teman-teman langsung di lokasi kami.
                    </p>
                    <span class="text-xs font-semibold text-brand-accent bg-brand-accent/10 px-3 py-1 rounded-full border border-brand-accent/20">Fasilitas VIP Lengkap</span>
                </div>

                <!-- Card COD / Ketemuan -->
                <div class="bg-brand-card p-8 rounded-2xl border border-brand-cardBorder hover:border-brand-accent/50 transition duration-300 relative group">
                    <div class="w-14 h-14 rounded-xl bg-amber-500/20 text-amber-400 flex items-center justify-center text-2xl mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-handshake"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">COD / Ketemuan</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Pilih lokasi titik temu kesepakatan bersama. Cocok bagi Anda yang ingin membawa unit sendiri dengan garansi pengecekan kelengkapan di tempat.
                    </p>
                    <span class="text-xs font-semibold text-amber-400 bg-amber-400/10 px-3 py-1 rounded-full border border-amber-400/20">Bebas Ongkir Antar</span>
                </div>

                <!-- Card Diantar Ke Rumah -->
                <div class="bg-brand-card p-8 rounded-2xl border border-brand-cardBorder hover:border-brand-accent/50 transition duration-300 relative group">
                    <div class="w-14 h-14 rounded-xl bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-2xl mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-truck-fast"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">Diantar Sampai Rumah</h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-4">
                        Kurir kami mengantar unit langsung ke rumah/kost/apartemen Anda, lengkap disettingkan sampai siap dimainkan tanpa ribet.
                    </p>
                    <span class="text-xs font-semibold text-emerald-400 bg-emerald-400/10 px-3 py-1 rounded-full border border-emerald-400/20">Paling Praktis</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Daftar Harga (Katalog) -->
    <section id="katalog" class="py-16 border-b border-brand-cardBorder">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="font-tech text-3xl font-bold text-white mb-2">DAFTAR HARGA RENTAL</h2>
                <p class="text-slate-400">Harga bersaing dengan jaminan unit prima dan game terupdate</p>
            </div>

            <!-- Pricing Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

                <!-- PS 4 Slim -->
                <div class="bg-brand-card rounded-2xl border border-brand-cardBorder overflow-hidden flex flex-col justify-between hover:border-brand-lightBlue transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <span class="text-xs uppercase font-bold text-brand-accent">Ekonomis</span>
                                <h3 class="text-2xl font-bold text-white">PlayStation 4 Slim</h3>
                            </div>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300 text-xs font-semibold">2 Stik DualShock</span>
                        </div>
                        <ul class="text-slate-300 text-sm space-y-3 mb-6">
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> PS4 Slim 500GB / 1TB</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Full Game (FC 24/25, GTA V, PES, dll)</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> 2 Stik Original Wireless</li>
                            <li class="flex items-center"><li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Kabel HDMI, Power & Charger Stik</li>
                        </ul>
                    </div>
                    <div class="bg-slate-900/60 p-6 border-t border-brand-cardBorder">
                        <div class="space-y-2 mb-4">
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Main di Tempat:</span>
                                <span class="text-white font-bold">Rp 10.000 / Jam</span>
                            </div>
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Sewa Home 12 Jam:</span>
                                <span class="text-white font-bold">Rp 60.000</span>
                            </div>
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Sewa Home 24 Jam:</span>
                                <span class="text-emerald-400 font-bold">Rp 90.000</span>
                            </div>
                        </div>
                        <a href="#order" onclick="selectConsole('ps4_slim')" class="block text-center w-full py-2.5 rounded-lg bg-brand-lightBlue hover:bg-brand-blue text-white font-semibold text-sm transition">Pilih PS4 Slim</a>
                    </div>
                </div>

                <!-- PS 4 Pro (Recommended) -->
                <div class="bg-brand-card rounded-2xl border-2 border-brand-accent overflow-hidden flex flex-col justify-between relative shadow-xl shadow-brand-accent/10">
                    <div class="bg-brand-accent text-brand-dark text-xs font-bold uppercase tracking-wider text-center py-1">Paling Populer</div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <span class="text-xs uppercase font-bold text-brand-accent">Performa 4K</span>
                                <h3 class="text-2xl font-bold text-white">PlayStation 4 Pro</h3>
                            </div>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300 text-xs font-semibold">2 Stik DualShock</span>
                        </div>
                        <ul class="text-slate-300 text-sm space-y-3 mb-6">
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Support Grafis 4K Boost Mode</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Kapasitas 1TB Full Game Terbaru</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> 2 Stik Original Wireless</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Kabel Lengkap & HDMI High Speed</li>
                        </ul>
                    </div>
                    <div class="bg-slate-900/60 p-6 border-t border-brand-cardBorder">
                        <div class="space-y-2 mb-4">
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Main di Tempat:</span>
                                <span class="text-white font-bold">Rp 15.000 / Jam</span>
                            </div>
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Sewa Home 12 Jam:</span>
                                <span class="text-white font-bold">Rp 80.000</span>
                            </div>
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Sewa Home 24 Jam:</span>
                                <span class="text-emerald-400 font-bold">Rp 120.000</span>
                            </div>
                        </div>
                        <a href="#order" onclick="selectConsole('ps4_pro')" class="block text-center w-full py-2.5 rounded-lg bg-brand-accent text-brand-dark hover:bg-cyan-300 font-bold text-sm transition">Pilih PS4 Pro</a>
                    </div>
                </div>

                <!-- PS 5 Next Gen -->
                <div class="bg-brand-card rounded-2xl border border-brand-cardBorder overflow-hidden flex flex-col justify-between hover:border-brand-lightBlue transition duration-300">
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <span class="text-xs uppercase font-bold text-purple-400">Next-Gen Experience</span>
                                <h3 class="text-2xl font-bold text-white">PlayStation 5</h3>
                            </div>
                            <span class="px-2.5 py-1 rounded bg-slate-800 text-slate-300 text-xs font-semibold">2 Stik DualSense</span>
                        </div>
                        <ul class="text-slate-300 text-sm space-y-3 mb-6">
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Performa Ultra HD 4K 120Hz</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Loading Cepat Ultra High SSD</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> 2 Stik DualSense Haptic Feedback</li>
                            <li class="flex items-center"><i class="fa-solid fa-check text-emerald-400 mr-2.5"></i> Game PS5 eksklusif (Tekken 8, Spiderman 2, dll)</li>
                        </ul>
                    </div>
                    <div class="bg-slate-900/60 p-6 border-t border-brand-cardBorder">
                        <div class="space-y-2 mb-4">
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Main di Tempat:</span>
                                <span class="text-white font-bold">Rp 25.000 / Jam</span>
                            </div>
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Sewa Home 12 Jam:</span>
                                <span class="text-white font-bold">Rp 150.000</span>
                            </div>
                            <div class="flex justify-between text-sm">
                                <span class="text-slate-400">Sewa Home 24 Jam:</span>
                                <span class="text-emerald-400 font-bold">Rp 220.000</span>
                            </div>
                        </div>
                        <a href="#order" onclick="selectConsole('ps5')" class="block text-center w-full py-2.5 rounded-lg bg-brand-lightBlue hover:bg-brand-blue text-white font-semibold text-sm transition">Pilih PS5</a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Interactive Order Form / Kalkulator -->
    <section id="order" class="py-16 bg-brand-dark/80">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-brand-card p-6 sm:p-10 rounded-3xl border border-brand-cardBorder shadow-2xl">
                <div class="text-center mb-8">
                    <h2 class="font-tech text-3xl font-bold text-white mb-2">FORMULIR PEMESANAN</h2>
                    <p class="text-slate-400 text-sm">Hitung otomatis estimasi biaya dan langsung hubungi kami via WhatsApp</p>
                </div>

                <form id="rentalForm" class="space-y-6" onsubmit="sendToWhatsApp(event)">
                    <!-- Nama & Kontak -->
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-slate-300 text-sm font-semibold mb-2">Nama Lengkap *</label>
                            <input type="text" id="nama" required placeholder="Masukkan nama Anda" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-accent text-sm">
                        </div>
                        <div>
                            <label class="block text-slate-300 text-sm font-semibold mb-2">Nomor WhatsApp *</label>
                            <input type="tel" id="telepon" required placeholder="Contoh: 08123456789" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-accent text-sm">
                        </div>
                    </div>

                    <!-- Tipe PS & Bentuk Pemesanan -->
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-slate-300 text-sm font-semibold mb-2">Pilih Tipe PlayStation *</label>
                            <select id="tipePs" onchange="calculateTotal()" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-accent text-sm">
                                <option value="ps4_slim">PlayStation 4 Slim</option>
                                <option value="ps4_pro">PlayStation 4 Pro</option>
                                <option value="ps5">PlayStation 5</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-slate-300 text-sm font-semibold mb-2">Bentuk Pemesanan *</label>
                            <select id="bentukPemesanan" onchange="calculateTotal()" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-accent text-sm">
                                <option value="tempat">Main di Tempat Rental</option>
                                <option value="cod">COD (Ketemuan di Titik Terentu)</option>
                                <option value="antar">Diantar Sampai Rumah (+Ongkir Rp 15rb)</option>
                            </select>
                        </div>
                    </div>

                    <!-- Durasi Rental -->
                    <div>
                        <label class="block text-slate-300 text-sm font-semibold mb-2">Durasi / Paket Waktu Sewa *</label>
                        <select id="durasi" onchange="calculateTotal()" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-accent text-sm">
                            <option value="per_jam">Per Jam (Main di Tempat)</option>
                            <option value="12_jam">Paket 12 Jam (Bawa Pulang / Delivery)</option>
                            <option value="24_jam" selected>Paket 24 Jam (1 Hari Full)</option>
                            <option value="48_jam">Paket 48 Jam (2 Hari Paket Hemat)</option>
                        </select>
                    </div>

                    <!-- Qty Jam jika per_jam -->
                    <div id="jumlahJamWrapper" class="hidden">
                        <label class="block text-slate-300 text-sm font-semibold mb-2">Berapa Jam? *</label>
                        <input type="number" id="jumlahJam" value="2" min="1" oninput="calculateTotal()" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-accent text-sm">
                    </div>

                    <!-- Alamat jika diantar -->
                    <div id="alamatWrapper">
                        <label class="block text-slate-300 text-sm font-semibold mb-2">Alamat Pengiriman / Detail Lokasi *</label>
                        <textarea id="alamat" rows="2" placeholder="Tuliskan alamat rumah / tempat ketemuan COD secara lengkap" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-accent text-sm"></textarea>
                    </div>

                    <!-- Total Estimasi -->
                    <div class="bg-slate-900/90 p-5 rounded-2xl border border-brand-cardBorder flex flex-col sm:flex-row justify-between items-center gap-4">
                        <div>
                            <span class="text-xs text-slate-400 uppercase font-semibold">Total Estimasi Biaya</span>
                            <div id="totalBiaya" class="text-3xl font-extrabold text-brand-accent">Rp 90.000</div>
                        </div>
                        <button type="submit" class="w-full sm:w-auto px-8 py-3.5 rounded-xl bg-emerald-500 hover:bg-emerald-600 text-white font-bold text-base shadow-lg shadow-emerald-500/25 transition duration-300 flex items-center justify-center space-x-3">
                            <i class="fa-brands fa-whatsapp text-xl"></i>
                            <span>Kirim Order via WhatsApp</span>
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Metode Pembayaran -->
    <section id="pembayaran" class="py-16 border-t border-brand-cardBorder bg-brand-dark">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="font-tech text-3xl font-bold text-white mb-3">METODE PEMBAYARAN</h2>
            <p class="text-slate-400 mb-10">Kami menerima berbagai pilihan transaksi non-tunai maupun tunai demi kenyamanan Anda</p>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 max-w-4xl mx-auto">
                <!-- E-Wallet -->
                <div class="bg-brand-card p-6 rounded-2xl border border-brand-cardBorder flex flex-col items-center justify-center space-y-2">
                    <i class="fa-solid fa-wallet text-3xl text-brand-accent mb-1"></i>
                    <span class="font-bold text-white text-base">E-Wallet</span>
                    <span class="text-xs text-slate-400">Gopay, OVO, DANA, ShopeePay</span>
                </div>

                <!-- Transfer Bank -->
                <div class="bg-brand-card p-6 rounded-2xl border border-brand-cardBorder flex flex-col items-center justify-center space-y-2">
                    <i class="fa-solid fa-building-columns text-3xl text-brand-lightBlue mb-1"></i>
                    <span class="font-bold text-white text-base">Transfer Bank</span>
                    <span class="text-xs text-slate-400">BCA, Mandiri, BRI, BNI</span>
                </div>

                <!-- QRIS -->
                <div class="bg-brand-card p-6 rounded-2xl border border-brand-cardBorder flex flex-col items-center justify-center space-y-2">
                    <i class="fa-solid fa-qrcode text-3xl text-purple-400 mb-1"></i>
                    <span class="font-bold text-white text-base">QRIS All Payment</span>
                    <span class="text-xs text-slate-400">Scan Praktis Semua Aplikasi</span>
                </div>

                <!-- Cash di Tempat/COD -->
                <div class="bg-brand-card p-6 rounded-2xl border border-brand-cardBorder flex flex-col items-center justify-center space-y-2">
                    <i class="fa-solid fa-money-bill-wave text-3xl text-emerald-400 mb-1"></i>
                    <span class="font-bold text-white text-base">Cash / Tunai</span>
                    <span class="text-xs text-slate-400">Bayar di Tempat / Pas COD</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 border-t border-brand-cardBorder py-8 text-center text-slate-500 text-sm">
        <div class="max-w-7xl mx-auto px-4">
            <p class="mb-2">© 2026 Rental Maulana PlayStation. All rights reserved.</p>
            <p class="text-xs text-slate-600">Layanan Rental PS4 & PS5 Terpercaya & Mengutamakan Kepuasan Pelanggan.</p>
        </div>
    </footer>

    <!-- JavaScript Logic -->
    <script>
        // Nomor WhatsApp Tujuan (Ganti sesuai nomor WhatsApp Anda)
        const WHATSAPP_NUMBER = "62895393728347";

        // Price Matrix
        const prices = {
            ps4_slim: {
                per_jam: 10000,
                '12_jam': 60000,
                '24_jam': 90000,
                '48_jam': 170000,
                name: "PlayStation 4 Slim"
            },
            ps4_pro: {
                per_jam: 15000,
                '12_jam': 80000,
                '24_jam': 120000,
                '48_jam': 230000,
                name: "PlayStation 4 Pro"
            },
            ps5: {
                per_jam: 25000,
                '12_jam': 150000,
                '24_jam': 220000,
                '48_jam': 420000,
                name: "PlayStation 5"
            }
        };

        function selectConsole(tipe) {
            document.getElementById('tipePs').value = tipe;
            calculateTotal();
        }

        function calculateTotal() {
            const tipe = document.getElementById('tipePs').value;
            const durasi = document.getElementById('durasi').value;
            const bentuk = document.getElementById('bentukPemesanan').value;
            const jumlahJamWrapper = document.getElementById('jumlahJamWrapper');
            const jumlahJam = parseInt(document.getElementById('jumlahJam').value) || 1;

            // Tampilkan field jam jika pilih per_jam
            if (durasi === 'per_jam') {
                jumlahJamWrapper.classList.remove('hidden');
            } else {
                jumlahJamWrapper.classList.add('hidden');
            }

            let subtotal = 0;
            if (durasi === 'per_jam') {
                subtotal = prices[tipe].per_jam * jumlahJam;
            } else {
                subtotal = prices[tipe][durasi];
            }

            // Tambahan Ongkir jika diantar
            let ongkir = 0;
            if (bentuk === 'antar') {
                ongkir = 15000;
            }

            const total = subtotal + ongkir;

            // Format Rupiah
            document.getElementById('totalBiaya').innerText = "Rp " + total.toLocaleString('id-ID');
            return { total, subtotal, ongkir };
        }

        function sendToWhatsApp(event) {
            event.preventDefault();

            const nama = document.getElementById('nama').value;
            const telepon = document.getElementById('telepon').value;
            const tipeKey = document.getElementById('tipePs').value;
            const tipeName = prices[tipeKey].name;
            const durasiKey = document.getElementById('durasi').value;
            const bentukKey = document.getElementById('bentukPemesanan').value;
            const jumlahJam = document.getElementById('jumlahJam').value;
            const alamat = document.getElementById('alamat').value || '-';
            
            const calc = calculateTotal();

            let durasiText = "";
            if (durasiKey === 'per_jam') {
                durasiText = `${jumlahJam} Jam`;
            } else if (durasiKey === '12_jam') {
                durasiText = "Paket 12 Jam";
            } else if (durasiKey === '24_jam') {
                durasiText = "Paket 24 Jam (1 Hari)";
            } else if (durasiKey === '48_jam') {
                durasiText = "Paket 48 Jam (2 Hari)";
            }

            let bentukText = "";
            if (bentukKey === 'tempat') bentukText = "Main di Tempat Rental";
            if (bentukKey === 'cod') bentukText = "COD (Ketemuan)";
            if (bentukKey === 'antar') bentukText = "Diantar Sampai Rumah (+Ongkir Rp 15.000)";

            // Format Pesan WhatsApp
            const message = `Halo Admin Rental Maulana,%0A%0ASaya ingin memesan rental PlayStation dengan detail berikut:%0A%0A` +
                `👤 *Nama:* ${nama}%0A` +
                `📞 *No. WA:* ${telepon}%0A` +
                `🎮 *Tipe PS:* ${tipeName}%0A` +
                `⏱️ *Durasi:* ${durasiText}%0A` +
                `📍 *Bentuk Pemesanan:* ${bentukText}%0A` +
                `🏡 *Alamat / Lokasi:* ${alamat}%0A%0A` +
                `💰 *Total Estimasi Biaya:* Rp ${calc.total.toLocaleString('id-ID')}%0A%0A` +
                `Mohon dikonfirmasi ketersediaan unitnya. Terima kasih!`;

            // Redirect ke WhatsApp
            window.open(`https://wa.me/${WHATSAPP_NUMBER}?text=${message}`, '_blank');
        }

        // Run calculation on load
        window.onload = function() {
            calculateTotal();
        }
    </script>
</body>
</html>
