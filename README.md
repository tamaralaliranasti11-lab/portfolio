<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tamara Lalira Nasti - Professional Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            50: '#f0f4f8',
                            100: '#d9e2ec',
                            800: '#1e3a8a',
                            900: '#0f172a',
                            950: '#090d16'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased selection:bg-navy-800 selection:text-white">

    <!-- 1. Header / Navbar Navigation -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <a href="#" class="font-bold text-xl tracking-tight text-navy-900">
                    TAMARA<span class="text-navy-800 font-light">.NASTI</span>
                </a>
                
                <!-- Desktop Navigation -->
                <nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-600">
                    <a href="#about" class="hover:text-navy-800 transition-colors">Tentang Saya</a>
                    <a href="#experience" class="hover:text-navy-800 transition-colors">Pengalaman</a>
                    <a href="#skills" class="hover:text-navy-800 transition-colors">Keahlian</a>
                    <a href="#education" class="hover:text-navy-800 transition-colors">Pendidikan</a>
                    <a href="#contact" class="hover:text-navy-800 transition-colors">Kontak</a>
                </nav>

                <div class="hidden md:flex items-center">
                    <a href="#contact" class="inline-flex items-center justify-center px-4 py-2 text-sm font-medium text-white bg-navy-900 rounded-lg shadow-sm hover:bg-navy-800 transition-colors">
                        Hubungi Saya
                    </a>
                </div>

                <!-- Mobile menu button -->
                <button id="menu-btn" class="md:hidden text-slate-600 hover:text-navy-900 focus:outline-none" aria-label="Toggle Menu">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Navigation -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-4 space-y-2">
            <a href="#about" class="block py-2 text-sm font-medium text-slate-700 hover:text-navy-800">Tentang Saya</a>
            <a href="#experience" class="block py-2 text-sm font-medium text-slate-700 hover:text-navy-800">Pengalaman</a>
            <a href="#skills" class="block py-2 text-sm font-medium text-slate-700 hover:text-navy-800">Keahlian</a>
            <a href="#education" class="block py-2 text-sm font-medium text-slate-700 hover:text-navy-800">Pendidikan</a>
            <a href="#contact" class="block py-2 text-sm font-medium text-slate-700 hover:text-navy-800">Kontak</a>
        </div>
    </header>

    <!-- 2. Hero Section -->
    <section class="relative pt-32 pb-20 md:pt-40 md:pb-28 overflow-hidden bg-gradient-to-b from-slate-100 to-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto">
                <span class="inline-block px-3 py-1 text-xs font-semibold uppercase tracking-wider text-navy-800 bg-navy-50 rounded-full border border-navy-100 mb-6">
                    Digital Marketing & Administration Professional
                </span>
                <h1 class="text-4xl sm:text-5xl md:text-6xl font-extrabold text-navy-900 tracking-tight leading-tight mb-6">
                    Rooted in Purpose, <br class="hidden sm:inline"/>Growing Beyond Borders
                </h1>
                <p class="text-lg md:text-xl text-slate-600 mb-8 leading-relaxed font-light">
                    Halo, saya <strong class="font-semibold text-navy-900">Tamara Lalira Nasti</strong>. Lulusan Manajemen Pendidikan yang memadukan ketelitian operasional administrasi dengan kreativitas komunikasi strategi pemasaran digital.
                </p>
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                    <a href="#contact" class="w-full sm:w-auto px-6 py-3 text-base font-medium text-white bg-navy-900 rounded-lg shadow-md hover:bg-navy-800 transition-all flex items-center justify-center gap-2">
                        <span>Mulai Kolaborasi</span>
                        <i class="fa-solid fa-arrow-right text-sm"></i>
                    </a>
                    <a href="#experience" class="w-full sm:w-auto px-6 py-3 text-base font-medium text-navy-900 bg-white border border-slate-300 rounded-lg shadow-sm hover:bg-slate-50 transition-all text-center">
                        Lihat Portofolio & Pengalaman
                    </a>
                </div>
            </div>
        </div>
        
        <!-- Subtle Background Pattern -->
        <div class="absolute inset-0 z-0 opacity-40 pointer-events-none">
            <div class="absolute -top-24 -right-24 w-96 h-96 bg-blue-100 rounded-full blur-3xl"></div>
            <div class="absolute top-1/2 -left-24 w-80 h-80 bg-slate-200 rounded-full blur-3xl"></div>
        </div>
    </section>

    <!-- 3. About Me Section -->
    <section id="about" class="py-20 bg-white border-y border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-5">
                    <div class="relative">
                        <div class="w-full h-96 bg-navy-900 rounded-2xl shadow-xl flex flex-col justify-between p-8 text-white relative overflow-hidden">
                            <div class="absolute top-0 right-0 transform translate-x-4 -translate-y-4 w-32 h-32 bg-navy-800 rounded-full opacity-50"></div>
                            <div>
                                <i class="fa-solid fa-graduation-cap text-4xl text-blue-300 mb-4"></i>
                                <h3 class="text-2xl font-bold mb-1">Tamara Lalira Nasti</h3>
                                <p class="text-blue-200 text-sm">Manajemen Pendidikan | S.Pd.</p>
                            </div>
                            <div class="border-t border-slate-700 pt-4">
                                <p class="text-xs text-slate-300 mb-1">Universitas Asal:</p>
                                <p class="font-medium text-sm">UIN Mahmud Yunus Batusangkar</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="lg:col-span-7">
                    <h2 class="text-3xl font-bold text-navy-900 mb-6">Tentang Saya</h2>
                    <p class="text-slate-600 leading-relaxed mb-4">
                        Saya adalah lulusan Manajemen Pendidikan dari UIN Mahmud Yunus Batusangkar yang teliti, adaptif, dan memiliki pengalaman praktis dalam operasional administrasi, pengarsipan dokumen, serta komunikasi organisasi.
                    </p>
                    <p class="text-slate-600 leading-relaxed mb-6">
                        Terbukti mampu mengelola surat-menyurat akademik, menyederhanakan proses kearsipan, serta mendesain aset grafis untuk kegiatan organisasi. Memiliki penguasaan teknis yang kuat dalam Microsoft Office dan perangkat desain grafis, dikombinasikan dengan keterampilan hubungan masyarakat yang sangat baik. 
                    </p>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4 pt-2">
                        <div class="p-4 rounded-xl bg-slate-50 border border-slate-200">
                            <div class="flex items-center gap-3 mb-2">
                                <div class="w-8 h-8 rounded-lg bg-navy-50 text-navy-800 flex items-center justify-center">
                                    <i class="fa-solid fa-bullhorn text-sm"></i>
                                </div>
                                <h4 class="font-bold text-navy-900">Digital Marketing</h4>
                            </div>
                            <p class="text-xs text-slate-600">Berpengalaman merancang aset promosi grafis, mengelola kampanye komunikasi, dan meningkatkan engagement program.</p>
                        </div>
                        <div class="p-4 rounded-xl bg-slate-50 border border-slate-200">
                            <div class="flex items-center gap-3 mb-2">
                                <div class="w-8 h-8 rounded-lg bg-navy-50 text-navy-800 flex items-center justify-center">
                                    <i class="fa-solid fa-folder-open text-sm"></i>
                                </div>
                                <h4 class="font-bold text-navy-900">Administration Staff</h4>
                            </div>
                            <p class="text-xs text-slate-600">Ahli dalam tata kelola arsip digital/fisik, pengolahan disposisi surat, dan pelayanan publik akurat berbasis integritas data.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Experience & Projects Section -->
    <section id="experience" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl font-bold text-navy-900 mb-4">Pengalaman & Rekam Jejak</h2>
                <p class="text-slate-600 text-sm sm:text-base">Kombinasi pengalaman profesional di bidang administrasi sekolah, akademis, serta kepemimpinan organisasi.</p>
            </div>

            <!-- Sub-section: Work Experience -->
            <div class="mb-14">
                <h3 class="text-xl font-bold text-navy-900 mb-6 flex items-center gap-2">
                    <i class="fa-solid fa-briefcase text-navy-800"></i> Pengalaman Kerja
                </h3>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Experience Card 1 -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-shadow">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h4 class="font-bold text-lg text-navy-900">Staff Administrasi</h4>
                                <p class="text-sm text-navy-800 font-medium">SMP N 4 Batusangkar</p>
                            </div>
                            <span class="text-xs px-2.5 py-1 bg-slate-100 text-slate-600 rounded-full font-medium">Juli 2025 – Agu 2025</span>
                        </div>
                        <ul class="space-y-2 text-sm text-slate-600">
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Mengelola surat-menyurat resmi, disposisi, dan sistem kearsipan (150+ dokumen/bulan, akurasi 100%).</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Menerapkan sistem pengindeksan digital & fisik, memangkas waktu pencarian dokumen hingga 35%.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Mengoordinasikan permintaan administratif lintas departemen untuk kelancaran operasional.</span>
                            </li>
                        </ul>
                    </div>

                    <!-- Experience Card 2 -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-shadow">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h4 class="font-bold text-lg text-navy-900">Magang Pelayanan Akademik (AKAMA)</h4>
                                <p class="text-sm text-navy-800 font-medium">UIN Mahmud Yunus Batusangkar</p>
                            </div>
                            <span class="text-xs px-2.5 py-1 bg-slate-100 text-slate-600 rounded-full font-medium">Sep 2025 – Okt 2025</span>
                        </div>
                        <ul class="space-y-2 text-sm text-slate-600">
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Memfasilitasi dukungan administrasi dan akademik untuk 200+ mahasiswa & dosen setiap hari.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Memperbarui catatan akademik berbasis MS Excel dengan menjaga integritas data 100%.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Menyiapkan dokumentasi resmi, surat keputusan, dan laporan institusi secara terstandar.</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Sub-section: Organizational Experience -->
            <div>
                <h3 class="text-xl font-bold text-navy-900 mb-6 flex items-center gap-2">
                    <i class="fa-solid fa-users text-navy-800"></i> Pengalaman Organisasi
                </h3>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Org Card 1 -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-shadow">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h4 class="font-bold text-lg text-navy-900">Sekretaris Umum</h4>
                                <p class="text-sm text-navy-800 font-medium">HMPS Manajemen Pendidikan</p>
                            </div>
                            <span class="text-xs px-2.5 py-1 bg-slate-100 text-slate-600 rounded-full font-medium">Mar 2023 – Des 2023</span>
                        </div>
                        <ul class="space-y-2 text-sm text-slate-600">
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Mengarahkan tata kelola administrasi organisasi serta menyusun 40+ surat resmi & proposal.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Mengelola komunikasi internal-eksternal lintas 5 departemen dan panitia kegiatan.</span>
                            </li>
                        </ul>
                    </div>

                    <!-- Org Card 2 -->
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm hover:shadow-md transition-shadow">
                        <div class="flex justify-between items-start mb-4">
                            <div>
                                <h4 class="font-bold text-lg text-navy-900">Staff Departemen Sosial Masyarakat</h4>
                                <p class="text-sm text-navy-800 font-medium">DEMA FTIK UIN Mahmud Yunus</p>
                            </div>
                            <span class="text-xs px-2.5 py-1 bg-slate-100 text-slate-600 rounded-full font-medium">Feb 2024 – Des 2024</span>
                        </div>
                        <ul class="space-y-2 text-sm text-slate-600">
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Merancang aset grafis promosi & konten digital pengabdian, meningkatkan engagement 25%.</span>
                            </li>
                            <li class="flex items-start gap-2">
                                <i class="fa-solid fa-check text-navy-800 text-xs mt-1"></i>
                                <span>Berkolaborasi dalam tim 12 orang mengeksekusi program bakti sosial berskala besar.</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. My Skills Section -->
    <section id="skills" class="py-20 bg-white border-y border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl font-bold text-navy-900 mb-4">Keahlian & Kompetensi</h2>
                <p class="text-slate-600 text-sm sm:text-base">Keahlian teknis dan interpersonal yang menunjang efisiensi kerja tinggi.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Hard Skills -->
                <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200">
                    <h3 class="text-lg font-bold text-navy-900 mb-6 flex items-center gap-2">
                        <i class="fa-solid fa-laptop-code text-navy-800"></i> Hard Skills (Keahlian Teknis)
                    </h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3.5 py-2 bg-white text-navy-900 text-sm font-medium rounded-lg border border-slate-200 shadow-sm flex items-center gap-2">
                            <i class="fa-brands fa-microsoft text-blue-600"></i> Microsoft Office (Word, Excel, PPT)
                        </span>
                        <span class="px-3.5 py-2 bg-white text-navy-900 text-sm font-medium rounded-lg border border-slate-200 shadow-sm flex items-center gap-2">
                            <i class="fa-solid fa-box-archive text-amber-600"></i> Manajemen Dokumen & Arsip
                        </span>
                        <span class="px-3.5 py-2 bg-white text-navy-900 text-sm font-medium rounded-lg border border-slate-200 shadow-sm flex items-center gap-2">
                            <i class="fa-solid fa-palette text-purple-600"></i> Desain Grafis
                        </span>
                        <span class="px-3.5 py-2 bg-white text-navy-900 text-sm font-medium rounded-lg border border-slate-200 shadow-sm flex items-center gap-2">
                            <i class="fa-solid fa-hashtag text-pink-600"></i> Pembuatan Konten Digital
                        </span>
                        <span class="px-3.5 py-2 bg-white text-navy-900 text-sm font-medium rounded-lg border border-slate-200 shadow-sm flex items-center gap-2">
                            <i class="fa-solid fa-comments text-emerald-600"></i> Public Relations
                        </span>
                        <span class="px-3.5 py-2 bg-white text-navy-900 text-sm font-medium rounded-lg border border-slate-200 shadow-sm flex items-center gap-2">
                            <i class="fa-solid fa-file-signature text-indigo-600"></i> Processing Surat & Disposisi
                        </span>
                    </div>
                </div>

                <!-- Soft Skills -->
                <div class="p-6 rounded-2xl bg-slate-50 border border-slate-200">
                    <h3 class="text-lg font-bold text-navy-900 mb-6 flex items-center gap-2">
                        <i class="fa-solid fa-user-gear text-navy-800"></i> Soft Skills (Keahlian Interpersonal)
                    </h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3.5 py-2 bg-white text-slate-800 text-sm font-medium rounded-lg border border-slate-200 shadow-sm">
                            Public Speaking
                        </span>
                        <span class="px-3.5 py-2 bg-white text-slate-800 text-sm font-medium rounded-lg border border-slate-200 shadow-sm">
                            Komunikasi Interpersonal
                        </span>
                        <span class="px-3.5 py-2 bg-white text-slate-800 text-sm font-medium rounded-lg border border-slate-200 shadow-sm">
                            Kerja Sama Tim (Teamwork)
                        </span>
                        <span class="px-3.5 py-2 bg-white text-slate-800 text-sm font-medium rounded-lg border border-slate-200 shadow-sm">
                            Manajemen Waktu
                        </span>
                        <span class="px-3.5 py-2 bg-white text-slate-800 text-sm font-medium rounded-lg border border-slate-200 shadow-sm">
                            Pemecahan Masalah
                        </span>
                        <span class="px-3.5 py-2 bg-white text-slate-800 text-sm font-medium rounded-lg border border-slate-200 shadow-sm">
                            Adaptabilitas High-Flex
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. Education Section -->
    <section id="education" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-12">
                <h2 class="text-3xl font-bold text-navy-900 mb-4">Latar Belakang Pendidikan</h2>
            </div>

            <div class="max-w-3xl mx-auto bg-white p-8 rounded-2xl border border-slate-200 shadow-sm">
                <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 mb-4 pb-4 border-b border-slate-100">
                    <div>
                        <h3 class="text-xl font-bold text-navy-900">Sarjana Pendidikan (S.Pd.) dalam Manajemen Pendidikan</h3>
                        <p class="text-navy-800 font-medium">UIN Mahmud Yunus Batusangkar</p>
                    </div>
                    <span class="px-3 py-1 bg-navy-50 text-navy-900 text-xs font-bold rounded-full border border-navy-100">
                        Angkatan 2026
                    </span>
                </div>
                <div class="flex items-center gap-2 text-slate-700 font-medium text-sm">
                    <span>Indeks Prestasi Kumulatif (IPK):</span>
                    <span class="px-2.5 py-0.5 bg-emerald-100 text-emerald-800 rounded font-bold">3.81 / 4.00</span>
                </div>
            </div>
        </div>
    </section>

    <!-- 7. Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                <!-- Contact Info -->
                <div class="lg:col-span-5">
                    <h2 class="text-3xl font-bold text-navy-900 mb-4">Mari Terhubung</h2>
                    <p class="text-slate-600 mb-8 leading-relaxed">
                        Terbuka untuk peluang karir di posisi **Digital Marketing Staff** maupun **Administration Staff**. Silakan hubungi saya melalui kontak di bawah ini.
                    </p>

                    <div class="space-y-6">
                        <div class="flex items-start gap-4">
                            <div class="w-10 h-10 rounded-lg bg-navy-50 text-navy-900 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="text-xs font-bold uppercase tracking-wider text-slate-400">Email</h4>
                                <a href="mailto:tamaralaliranasti11@gmail.com" class="text-sm font-medium text-navy-900 hover:text-navy-800">
                                    tamaralaliranasti11@gmail.com
                                </a>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-10 h-10 rounded-lg bg-navy-50 text-navy-900 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="text-xs font-bold uppercase tracking-wider text-slate-400">Telepon / WhatsApp</h4>
                                <a href="https://wa.me/6285278052854" target="_blank" class="text-sm font-medium text-navy-900 hover:text-navy-800">
                                    +62 852 7805 2854
                                </a>
                            </div>
                        </div>

                        <div class="flex items-start gap-4">
                            <div class="w-10 h-10 rounded-lg bg-navy-50 text-navy-900 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="text-xs font-bold uppercase tracking-wider text-slate-400">Lokasi</h4>
                                <p class="text-sm font-medium text-navy-900">
                                    Batusangkar, Sumatra Barat, Indonesia
                                </p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Contact Form -->
                <div class="lg:col-span-7 bg-slate-50 p-8 rounded-2xl border border-slate-200">
                    <h3 class="text-xl font-bold text-navy-900 mb-6">Kirim Pesan Direct</h3>
                    <form onsubmit="event.preventDefault(); alert('Pesan Anda berhasil terkirim!');" class="space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Nama Lengkap</label>
                                <input type="text" required placeholder="Nama Anda" class="w-full px-4 py-2.5 rounded-lg bg-white border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-navy-900">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Alamat Email</label>
                                <input type="email" required placeholder="email@domain.com" class="w-full px-4 py-2.5 rounded-lg bg-white border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-navy-900">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Subjek</label>
                            <input type="text" required placeholder="Tujuan pesan / Penawaran Posisi" class="w-full px-4 py-2.5 rounded-lg bg-white border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-navy-900">
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-700 uppercase mb-1">Pesan</label>
                            <textarea rows="4" required placeholder="Tuliskan pesan Anda di sini..." class="w-full px-4 py-2.5 rounded-lg bg-white border border-slate-300 text-sm focus:outline-none focus:ring-2 focus:ring-navy-900"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3 px-6 text-sm font-medium text-white bg-navy-900 rounded-lg hover:bg-navy-800 transition-colors shadow-md">
                            Kirim Pesan
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- 8. Footer -->
    <footer class="bg-navy-950 text-slate-400 py-8 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-4">
            <p class="text-xs">
                &copy; 2026 Tamara Lalira Nasti. All rights reserved.
            </p>
            <p class="text-xs text-slate-500">
                Designed for Digital Marketing & Administration Roles.
            </p>
        </div>
    </footer>

    <!-- Interactive Mobile Menu Script -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking menu links
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
