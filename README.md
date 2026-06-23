<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium Solid Surface | Top Table & Interior Custom</title>
    <meta name="description" content="Penyedia layanan instalasi Top Table Kitchen, Meja Resepsionis, dan Wastafel menggunakan bahan Solid Surface premium, tanpa sambungan dan anti bakteri.">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- AOS Animation CSS -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        primary: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0ea5e9',
                            600: '#0284c7',
                            900: '#0c4a6e',
                        },
                        dark: '#1e293b'
                    }
                }
            }
        }
    </script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
            -webkit-font-smoothing: antialiased;
        }
        
        .glass-nav {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(0,0,0,0.05);
        }

        /* Lightbox Styles */
        #lightbox {
            display: none;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        #lightbox.active {
            display: flex;
            opacity: 1;
        }

        .img-hover-zoom {
            overflow: hidden;
        }
        .img-hover-zoom img {
            transition: transform 0.5s ease;
        }
        .img-hover-zoom:hover img {
            transform: scale(1.05);
        }

        /* Gradient Overlay for Hero */
        .hero-overlay {
            background: linear-gradient(to right, rgba(15, 23, 42, 0.9) 0%, rgba(15, 23, 42, 0.4) 100%);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- Navbar -->
    <nav id="navbar" class="fixed w-full z-50 transition-all duration-300 bg-white/90 backdrop-blur-md shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- Logo -->
                <div class="flex-shrink-0 flex items-center gap-2 cursor-pointer" onclick="window.scrollTo(0,0)">
                    <div class="w-10 h-10 bg-primary-600 rounded-lg flex items-center justify-center text-white font-bold text-xl shadow-lg">
                        O
                    </div>
                    <span class="font-bold text-2xl tracking-tight text-slate-900">ONE<span class="text-primary-600">Solid</span></span>
                </div>

                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-8 items-center">
                    <a href="#beranda" class="text-slate-600 hover:text-primary-600 font-medium transition-colors">Beranda</a>
                    <a href="#keunggulan" class="text-slate-600 hover:text-primary-600 font-medium transition-colors">Keunggulan</a>
                    <a href="#koleksi" class="text-slate-600 hover:text-primary-600 font-medium transition-colors">Koleksi Warna</a>
                    <a href="#portofolio" class="text-slate-600 hover:text-primary-600 font-medium transition-colors">Portofolio</a>
                    <a href="#kontak" class="bg-primary-600 hover:bg-primary-500 text-white px-6 py-2.5 rounded-full font-medium transition-all shadow-md hover:shadow-lg flex items-center gap-2">
                        <i class="fab fa-whatsapp"></i> Hubungi Kami
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-600 hover:text-slate-900 focus:outline-none p-2">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Panel -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-slate-100 absolute w-full shadow-lg">
            <div class="px-4 pt-2 pb-6 space-y-2">
                <a href="#beranda" class="block px-3 py-3 text-base font-medium text-slate-700 hover:bg-slate-50 hover:text-primary-600 rounded-md">Beranda</a>
                <a href="#keunggulan" class="block px-3 py-3 text-base font-medium text-slate-700 hover:bg-slate-50 hover:text-primary-600 rounded-md">Keunggulan</a>
                <a href="#koleksi" class="block px-3 py-3 text-base font-medium text-slate-700 hover:bg-slate-50 hover:text-primary-600 rounded-md">Koleksi Warna</a>
                <a href="#portofolio" class="block px-3 py-3 text-base font-medium text-slate-700 hover:bg-slate-50 hover:text-primary-600 rounded-md">Portofolio</a>
                <a href="#kontak" class="block px-3 py-3 text-base font-medium bg-primary-50 text-primary-700 rounded-md mt-4">
                    <i class="fab fa-whatsapp mr-2"></i> Konsultasi Gratis
                </a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="beranda" class="relative pt-20 pb-32 flex items-center min-h-[90vh]">
        <!-- Background Image -->
        <div class="absolute inset-0 z-0">
            <img src="IMG-20260519-WA0036.jpg" alt="Kitchen Top Solid Surface" class="w-full h-full object-cover object-center" />
            <div class="absolute inset-0 hero-overlay"></div>
        </div>

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 w-full">
            <div class="max-w-3xl" data-aos="fade-up" data-aos-duration="1000">
                <span class="inline-block py-1 px-3 rounded-full bg-primary-500/20 text-primary-100 text-sm font-semibold tracking-wider mb-6 border border-primary-400/30">
                    MATERIAL INTERIOR PREMIUM
                </span>
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white leading-tight mb-6">
                    Wujudkan Dapur & Interior Impian Tanpa Batas
                </h1>
                <p class="text-lg md:text-xl text-slate-300 mb-10 max-w-2xl leading-relaxed">
                    Spesialis fabrikasi dan instalasi <strong>Solid Surface</strong> untuk Top Table Kitchen Set, Meja Resepsionis, dan Wastafel. Tampilan mewah, higienis, dan tanpa sambungan.
                </p>
                <div class="flex flex-wrap gap-4">
                    <a href="#koleksi" class="bg-white text-slate-900 hover:bg-slate-100 px-8 py-3.5 rounded-full font-semibold transition-all shadow-lg text-center flex-1 sm:flex-none">
                        Lihat Motif & Warna
                    </a>
                    <a href="#kontak" class="bg-primary-600 hover:bg-primary-500 text-white border border-primary-500 px-8 py-3.5 rounded-full font-semibold transition-all shadow-lg flex items-center justify-center gap-2 flex-1 sm:flex-none">
                        <i class="fab fa-whatsapp text-lg"></i> Pesan Sekarang
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Keunggulan Section -->
    <section id="keunggulan" class="py-24 bg-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16" data-aos="fade-up">
                <h2 class="text-primary-600 font-semibold tracking-wide uppercase text-sm mb-2">Mengapa Memilih Kami?</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-slate-900 mb-4">Keunggulan Solid Surface</h3>
                <p class="text-slate-600 text-lg">Material modern pengganti marmer dan granit tradisional dengan kelebihan yang tidak dimiliki batu alam.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Feature 1 -->
                <div class="bg-slate-50 rounded-2xl p-8 border border-slate-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-1 group" data-aos="fade-up" data-aos-delay="100">
                    <div class="w-14 h-14 bg-blue-100 text-primary-600 rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-primary-600 group-hover:text-white transition-colors">
                        <i class="fas fa-link-slash"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900 mb-3">Tanpa Sambungan</h4>
                    <p class="text-slate-600 leading-relaxed">Bisa disambung dengan sempurna hingga terlihat seperti satu kesatuan utuh, sangat estetis untuk area luas.</p>
                </div>
                <!-- Feature 2 -->
                <div class="bg-slate-50 rounded-2xl p-8 border border-slate-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-1 group" data-aos="fade-up" data-aos-delay="200">
                    <div class="w-14 h-14 bg-emerald-100 text-emerald-600 rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-emerald-600 group-hover:text-white transition-colors">
                        <i class="fas fa-shield-virus"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900 mb-3">Anti Bakteri & Jamur</h4>
                    <p class="text-slate-600 leading-relaxed">Permukaan tidak berpori (non-porous) sehingga noda, air, bakteri, dan jamur tidak dapat menyerap ke dalam.</p>
                </div>
                <!-- Feature 3 -->
                <div class="bg-slate-50 rounded-2xl p-8 border border-slate-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-1 group" data-aos="fade-up" data-aos-delay="300">
                    <div class="w-14 h-14 bg-orange-100 text-orange-600 rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-orange-600 group-hover:text-white transition-colors">
                        <i class="fas fa-hammer"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900 mb-3">Lentur & Mudah Dibentuk</h4>
                    <p class="text-slate-600 leading-relaxed">Material ini bisa dipanaskan dan dibentuk melengkung (thermoforming) menyesuaikan desain custom Anda.</p>
                </div>
                <!-- Feature 4 -->
                <div class="bg-slate-50 rounded-2xl p-8 border border-slate-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-1 group" data-aos="fade-up" data-aos-delay="400">
                    <div class="w-14 h-14 bg-purple-100 text-purple-600 rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-purple-600 group-hover:text-white transition-colors">
                        <i class="fas fa-palette"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900 mb-3">Perawatan Mudah</h4>
                    <p class="text-slate-600 leading-relaxed">Sangat mudah dibersihkan. Jika tergores atau kusam seiring waktu, dapat dipoles ulang agar tampak baru kembali.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Detail Material & Ketebalan -->
    <section class="py-20 bg-slate-50 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col lg:flex-row items-center gap-16">
                <div class="w-full lg:w-1/2" data-aos="fade-right">
                    <div class="relative rounded-2xl overflow-hidden shadow-2xl">
                        <!-- Image showing thickness -->
                        <img src="IMG-20260529-WA0006.jpg" alt="Ketebalan Solid Surface" class="w-full h-auto object-cover hover:scale-105 transition-transform duration-700 cursor-pointer" onclick="openLightbox(this.src)">
                        <div class="absolute bottom-4 right-4 bg-white/90 backdrop-blur px-4 py-2 rounded-lg shadow-sm text-sm font-semibold">
                            <i class="fas fa-search-plus text-primary-600 mr-1"></i> Klik untuk perbesar
                        </div>
                    </div>
                </div>
                <div class="w-full lg:w-1/2" data-aos="fade-left">
                    <h3 class="text-3xl font-bold text-slate-900 mb-6">Ketebalan Ideal & Kualitas Solid Terjamin</h3>
                    <p class="text-slate-600 text-lg mb-6 leading-relaxed">
                        Kami menggunakan material solid surface dengan ketebalan standar pabrikasi premium (umumnya 9-12mm) yang memberikan kekuatan maksimal untuk area kerja dapur yang berat.
                    </p>
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-primary-500 mt-1 mr-3 text-xl"></i>
                            <div>
                                <strong class="block text-slate-900">Material Solid 100%</strong>
                                <span class="text-slate-600">Warna dan corak tembus dari permukaan hingga ke bagian dalam.</span>
                            </div>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-primary-500 mt-1 mr-3 text-xl"></i>
                            <div>
                                <strong class="block text-slate-900">Tahan Benturan Terukur</strong>
                                <span class="text-slate-600">Komposisi akrilik dan resin berkualitas membuatnya kokoh namun tidak getas seperti batu alam.</span>
                            </div>
                        </li>
                    </ul>
                    <a href="#koleksi" class="inline-flex items-center text-primary-600 font-semibold hover:text-primary-800 transition-colors">
                        Jelajahi Pilihan Warna Kami <i class="fas fa-arrow-right ml-2 mt-1"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Koleksi Warna Section (Samples) -->
    <section id="koleksi" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16" data-aos="fade-up">
                <h2 class="text-primary-600 font-semibold tracking-wide uppercase text-sm mb-2">Pilihan Tanpa Batas</h2>
                <h3 class="text-3xl md:text-4xl font-bold text-slate-900 mb-4">Koleksi Warna & Motif</h3>
                <p class="text-slate-600 text-lg">Dari warna solid minimalis, bintik (terrazzo), hingga corak urat marmer yang mewah. Temukan gaya yang paling cocok untuk interior Anda.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Sample Card 1 -->
                <div class="bg-white rounded-2xl shadow-md overflow-hidden border border-slate-100 img-hover-zoom cursor-pointer" data-aos="zoom-in" data-aos-delay="100" onclick="openLightbox('Screenshot_20260505-010718.jpg')">
                    <div class="h-64 relative bg-slate-100 flex items-center justify-center overflow-hidden">
                        <img src="Screenshot_20260505-010718.jpg" alt="Sample Solid Surface Motif Bintik Besar" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-black/0 hover:bg-black/10 transition-colors flex items-center justify-center opacity-0 hover:opacity-100">
                            <i class="fas fa-expand text-white text-3xl drop-shadow-md"></i>
                        </div>
                    </div>
                    <div class="p-6 text-center">
                        <h4 class="font-bold text-lg text-slate-900">Motif Bintik & Terrazzo</h4>
                        <p class="text-sm text-slate-500 mt-2">Koleksi populer untuk gaya modern kontemporer.</p>
                    </div>
                </div>

                <!-- Sample Card 2 -->
                <div class="bg-white rounded-2xl shadow-md overflow-hidden border border-slate-100 img-hover-zoom cursor-pointer" data-aos="zoom-in" data-aos-delay="200" onclick="openLightbox('Screenshot_20260505-182556.jpg')">
                    <div class="h-64 relative bg-slate-100 flex items-center justify-center overflow-hidden">
                        <img src="Screenshot_20260505-182556.jpg" alt="Katalog Warna Solid Surface Lengkap" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-black/0 hover:bg-black/10 transition-colors flex items-center justify-center opacity-0 hover:opacity-100">
                            <i class="fas fa-expand text-white text-3xl drop-shadow-md"></i>
                        </div>
                    </div>
                    <div class="p-6 text-center">
                        <h4 class="font-bold text-lg text-slate-900">Solid Color & Translucent</h4>
                        <p class="text-sm text-slate-500 mt-2">Pilihan warna warni yang kaya dan bahan yang dapat tembus cahaya.</p>
                    </div>
                </div>

                <!-- Sample Card 3 -->
                <div class="bg-white rounded-2xl shadow-md overflow-hidden border border-slate-100 img-hover-zoom cursor-pointer" data-aos="zoom-in" data-aos-delay="300" onclick="openLightbox('IMG_20260508_102742_500.jpg')">
                    <div class="h-64 relative bg-slate-100 flex items-center justify-center overflow-hidden">
                        <img src="IMG_20260508_102742_500.jpg" alt="Close up Tekstur Solid Surface" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-black/0 hover:bg-black/10 transition-colors flex items-center justify-center opacity-0 hover:opacity-100">
                            <i class="fas fa-expand text-white text-3xl drop-shadow-md"></i>
                        </div>
                    </div>
                    <div class="p-6 text-center">
                        <h4 class="font-bold text-lg text-slate-900">Granit & Sand Texture</h4>
                        <p class="text-sm text-slate-500 mt-2">Tekstur elegan menyerupai pasir putih dan batuan alam.</p>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <p class="text-slate-500 italic text-sm">* Warna pada foto mungkin sedikit berbeda dari aslinya karena pencahayaan. Hubungi kami untuk melihat sampel fisik secara langsung.</p>
            </div>
        </div>
    </section>

    <!-- Portfolio/Gallery Section -->
    <section id="portofolio" class="py-24 bg-slate-900 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row justify-between items-end mb-12" data-aos="fade-up">
                <div class="max-w-2xl">
                    <h2 class="text-primary-400 font-semibold tracking-wide uppercase text-sm mb-2">Galeri Proyek</h2>
                    <h3 class="text-3xl md:text-4xl font-bold mb-4">Hasil Karya Pemasangan Kami</h3>
                    <p class="text-slate-400">Pekerjaan rapi, detail presisi, dan hasil akhir yang memukau. Berbagai aplikasi solid surface pada residensial dan komersial.</p>
                </div>
                <div class="mt-6 md:mt-0">
                    <a href="#kontak" class="text-white border-b-2 border-primary-500 pb-1 hover:text-primary-400 transition-colors font-medium">Mulai Proyek Anda</a>
                </div>
            </div>

            <!-- Gallery Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                
                <!-- Gallery Item 1: Curved Reception Desk 1 -->
                <div class="group relative rounded-xl overflow-hidden cursor-pointer" data-aos="fade-up" data-aos-delay="100" onclick="openLightbox('IMG_20260602_163704_115.jpg')">
                    <div class="aspect-[4/3] bg-slate-800">
                        <img src="IMG_20260602_163704_115.jpg" alt="Instalasi Meja Resepsionis Lengkung" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-90 group-hover:opacity-100">
                    </div>
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
                        <h4 class="text-xl font-bold text-white mb-1">Meja Counter Custom</h4>
                        <p class="text-primary-300 text-sm">Instalasi melengkung seamless</p>
                    </div>
                </div>

                <!-- Gallery Item 2: Modern Glowing Desk -->
                <div class="group relative rounded-xl overflow-hidden cursor-pointer" data-aos="fade-up" data-aos-delay="200" onclick="openLightbox('IMG_20260505_001541_506.jpg')">
                    <div class="aspect-[4/3] bg-slate-800">
                        <img src="IMG_20260505_001541_506.jpg" alt="Meja Resepsionis Modern dengan Lampu LED" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-90 group-hover:opacity-100">
                    </div>
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
                        <h4 class="text-xl font-bold text-white mb-1">Modern Reception Desk</h4>
                        <p class="text-primary-300 text-sm">Finishing glossy dengan LED</p>
                    </div>
                </div>

                <!-- Gallery Item 3: Mint Kitchen Top -->
                <div class="group relative rounded-xl overflow-hidden cursor-pointer" data-aos="fade-up" data-aos-delay="300" onclick="openLightbox('IMG_20260520_161825_775.jpg')">
                    <div class="aspect-[4/3] bg-slate-800">
                        <img src="IMG_20260520_161825_775.jpg" alt="Top Table Dapur Warna Mint" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-90 group-hover:opacity-100">
                    </div>
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
                        <h4 class="text-xl font-bold text-white mb-1">Top Table Kitchen Set</h4>
                        <p class="text-primary-300 text-sm">Warna mint segar dengan backsplash</p>
                    </div>
                </div>

                <!-- Gallery Item 4: Dark Kitchen Top -->
                <div class="group relative rounded-xl overflow-hidden cursor-pointer" data-aos="fade-up" data-aos-delay="400" onclick="openLightbox('IMG_20260508_230118_732.jpg')">
                    <div class="aspect-[4/3] bg-slate-800">
                        <img src="IMG_20260508_230118_732.jpg" alt="Dapur Minimalis Top Table Gelap" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-90 group-hover:opacity-100">
                    </div>
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
                        <h4 class="text-xl font-bold text-white mb-1">Dapur Elegan Minimalis</h4>
                        <p class="text-primary-300 text-sm">Warna dark grey bintik, anti noda</p>
                    </div>
                </div>

                <!-- Gallery Item 5: Bathroom Vanity Sink -->
                <div class="group relative rounded-xl overflow-hidden cursor-pointer" data-aos="fade-up" data-aos-delay="500" onclick="openLightbox('IMG_20260515_115554_416.jpg')">
                    <div class="aspect-[4/3] bg-slate-800">
                        <img src="IMG_20260515_115554_416.jpg" alt="Wastafel Vanity Bathroom Solid Surface" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-90 group-hover:opacity-100">
                    </div>
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
                        <h4 class="text-xl font-bold text-white mb-1">Vanity Wastafel</h4>
                        <p class="text-primary-300 text-sm">Wastafel integrasi seamless tanpa celah</p>
                    </div>
                </div>

                <!-- Gallery Item 6: Curved Desk Alternate View -->
                <div class="group relative rounded-xl overflow-hidden cursor-pointer" data-aos="fade-up" data-aos-delay="600" onclick="openLightbox('IMG_20260602_163715_480.jpg')">
                    <div class="aspect-[4/3] bg-slate-800">
                        <img src="IMG_20260602_163715_480.jpg" alt="Meja Resepsionis Lengkung Angle Lain" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-90 group-hover:opacity-100">
                    </div>
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
                        <h4 class="text-xl font-bold text-white mb-1">Detail Melengkung</h4>
                        <p class="text-primary-300 text-sm">Pengerjaan presisi untuk area komersial</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- CTA / Contact Section -->
    <section id="kontak" class="relative py-24 bg-white overflow-hidden">
        <!-- Background Pattern -->
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-64 h-64 rounded-full bg-primary-50 opacity-50 blur-3xl"></div>
        <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 rounded-full bg-blue-50 opacity-50 blur-3xl"></div>

        <div class="relative z-10 max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center" data-aos="zoom-in">
            <h2 class="text-3xl md:text-5xl font-bold text-slate-900 mb-6">Siap Mengubah Tampilan Ruangan Anda?</h2>
            <p class="text-lg text-slate-600 mb-10 max-w-2xl mx-auto">
                Konsultasikan kebutuhan desain, ukuran, dan motif dengan tim ahli kami secara gratis. Dapatkan penawaran harga terbaik untuk proyek Anda.
            </p>
            
            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <!-- Replace '088223729333' with actual WhatsApp number -->
                <a href="https://wa.me/6288223729333" target="_blank" class="w-full sm:w-auto bg-green-500 hover:bg-green-600 text-white px-8 py-4 rounded-full font-bold text-lg transition-all shadow-lg hover:shadow-xl hover:-translate-y-1 flex items-center justify-center gap-3">
                    <i class="fab fa-whatsapp text-2xl"></i> Chat WhatsApp Sekarang
                </a>
                <a href="tel:+628823729333" class="w-full sm:w-auto bg-white text-slate-700 border border-slate-200 hover:bg-slate-50 px-8 py-4 rounded-full font-bold text-lg transition-all shadow-sm flex items-center justify-center gap-3">
                    <i class="fas fa-phone"></i> Hubungi via Telepon
                </a>
            </div>
            
            <div class="mt-12 flex flex-col md:flex-row justify-center items-center gap-8 text-slate-500 text-sm">
                <div class="flex items-center gap-2">
                    <i class="fas fa-ruler-combined text-primary-500 text-xl"></i>
                    <span>Gratis Survey & Pengukuran*</span>
                </div>
                <div class="flex items-center gap-2">
                    <i class="fas fa-shield-halved text-primary-500 text-xl"></i>
                    <span>Garansi Pemasangan</span>
                </div>
                <div class="flex items-center gap-2">
                    <i class="fas fa-truck-fast text-primary-500 text-xl"></i>
                    <span>Pengiriman Tepat Waktu</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 text-slate-400 py-12 border-t border-slate-900">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-3 gap-8">
            <div>
                <div class="flex items-center gap-2 mb-6">
                    <div class="w-8 h-8 bg-primary-600 rounded text-white flex items-center justify-center font-bold">
                        O
                    </div>
                    <span class="font-bold text-xl text-white">ONE<span class="text-primary-500">Solid</span></span>
                </div>
                <p class="mb-4">Solusi terbaik untuk kebutuhan interior berbahan Solid Surface berkualitas tinggi, dikerjakan oleh tenaga profesional berpengalaman.</p>
            </div>
            
            <div>
                <h4 class="text-white font-semibold mb-6">Layanan Kami</h4>
                <ul class="space-y-3">
                    <li><a href="#" class="hover:text-primary-400 transition-colors">Top Table Kitchen Set</a></li>
                    <li><a href="#" class="hover:text-primary-400 transition-colors">Meja Resepsionis / Counter</a></li>
                    <li><a href="#" class="hover:text-primary-400 transition-colors">Wastafel & Vanity Bathroom</a></li>
                    <li><a href="#" class="hover:text-primary-400 transition-colors">Poles Ulang & Perbaikan</a></li>
                </ul>
            </div>

            <div>
                <h4 class="text-white font-semibold mb-6">Informasi Kontak</h4>
                <ul class="space-y-4">
                    <li class="flex items-start gap-3">
                        <i class="fas fa-map-marker-alt mt-1 text-primary-500"></i>
                        <span>Kp.Rawajamun rt.001/rw.004, Dayeuh, Cileungsi, Bogor (16820),<br>Indonesia</span>
                    </li>
                    <li class="flex items-center gap-3">
                        <i class="fas fa-phone text-primary-500"></i>
                        <span>+62 882 2372 9333</span>
                    </li>
                </ul>
            </div>
        </div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mt-12 pt-8 border-t border-slate-800 text-center text-sm">
            <p>&copy; 2026 ONESolid Surface. All rights reserved.</p>
        </div>
    </footer>

    <!-- Lightbox Modal -->
    <div id="lightbox" class="fixed inset-0 z-[60] bg-black/90 items-center justify-center p-4 backdrop-blur-sm" onclick="closeLightbox(event)">
        <button onclick="closeLightboxBtn()" class="absolute top-6 right-6 text-white hover:text-primary-400 text-4xl focus:outline-none transition-colors">
            <i class="fas fa-times"></i>
        </button>
        <img id="lightbox-img" src="" alt="Enlarged View" class="max-w-full max-h-[90vh] object-contain rounded-lg shadow-2xl" onclick="event.stopPropagation()">
    </div>

    <!-- Scripts -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Initialize AOS Animation
        AOS.init({
            once: true,
            offset: 50,
            duration: 800,
            easing: 'ease-out-cubic',
        });

        // Navbar Scroll Effect
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 20) {
                navbar.classList.add('shadow-md');
                navbar.classList.remove('bg-white/90', 'shadow-sm');
                navbar.classList.add('bg-white');
            } else {
                navbar.classList.remove('shadow-md', 'bg-white');
                navbar.classList.add('bg-white/90', 'shadow-sm');
            }
        });

        // Mobile Menu Toggle
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');
        const menuLinks = menu.querySelectorAll('a');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Close mobile menu on link click
        menuLinks.forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });

        // Lightbox Logic
        const lightbox = document.getElementById('lightbox');
        const lightboxImg = document.getElementById('lightbox-img');

        function openLightbox(imageSrc) {
            lightboxImg.src = imageSrc;
            lightbox.classList.add('active');
            document.body.style.overflow = 'hidden'; // Prevent scrolling
        }

        function closeLightbox(e) {
            // Close if clicking outside the image
            if (e.target === lightbox) {
                closeLightboxBtn();
            }
        }

        function closeLightboxBtn() {
            lightbox.classList.remove('active');
            // Wait for fade out transition before hiding
            setTimeout(() => {
                lightboxImg.src = '';
                document.body.style.overflow = 'auto'; // Restore scrolling
            }, 300);
        }

        // Close Lightbox on Escape key
        document.addEventListener('keydown', (e) => {
            if (e.key === 'Escape' && lightbox.classList.contains('active')) {
                closeLightboxBtn();
            }
        });
    </script>
</body>
</html>
