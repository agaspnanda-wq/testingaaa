<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edukasi: Tekanan Sosial & Solusi Rent A Family</title>
    <!-- Tailwind CSS CDN untuk styling modern dan responsif -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Google Inter untuk tipografi yang bersih -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Latar belakang abu-abu sangat muda */
        }
        .container-content {
            background-color: #ffffff;
            border-radius: 1.5rem; /* Sudut lebih membulat */
        }
        .text-section p {
            margin-bottom: 1.25rem;
            line-height: 1.75;
        }
        .btn-primary {
            transition: transform 0.2s ease-in-out;
        }
        .btn-primary:hover {
            transform: translateY(-2px);
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Kontainer Utama -->
    <div id="main-container" class="max-w-4xl mx-auto container-content shadow-2xl my-8 p-4 md:p-8 lg:p-12">

        <!-- Halaman Edukasi (Akan disembunyikan saat beralih ke halaman form) -->
        <div id="edu-page">
            <!-- Header -->
            <header class="text-center py-12 px-6 bg-gradient-to-r from-blue-500 to-indigo-600 text-white rounded-t-2xl">
                <h1 class="text-3xl md:text-5xl font-bold mb-2 tracking-tight">Tekanan Sosial & Kesehatan Mental</h1>
                <p class="text-lg md:text-xl font-light opacity-90">Memahami Dampak dan Menemukan Solusi</p>
            </header>

            <!-- Bagian Konten Edukasi -->
            <main class="p-8 md:p-12">
                <!-- Bagian 1: Memahami Tekanan Sosial -->
                <section class="text-section mb-12">
                    <h2 class="text-2xl md:text-3xl font-semibold text-indigo-700 mb-4">Apa Itu Tekanan Sosial?</h2>
                    
                    <p>
                        Tekanan sosial adalah kekuatan atau pengaruh dari orang lain atau kelompok yang mendorong individu untuk menyesuaikan diri dengan norma, perilaku, atau ekspektasi tertentu. Dalam konteks keluarga, ini bisa berarti tekanan untuk segera menikah, memiliki anak, atau bahkan sekadar membawa pasangan atau keluarga lengkap ke sebuah acara.
                    </p>
                    <p>
                        Meskipun sering dianggap sepele, tekanan ini bisa menjadi beban berat yang secara signifikan mempengaruhi kesejahteraan mental dan emosional seseorang.
                    </p>
                </section>

                <!-- Bagian 2: Bahaya Tekanan Sosial pada Mental -->
                <section class="text-section mb-12">
                    <h2 class="text-2xl md:text-3xl font-semibold text-indigo-700 mb-4">Dampak Negatif pada Mental & Psikologi</h2>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                        <div>
                            <h3 class="font-medium text-lg text-gray-600 mb-2">1. Kecemasan & Stres</h3>
                            <p>
                                Ekspektasi yang tidak realistis dari lingkungan bisa memicu kecemasan berlebihan, terutama saat menghadapi acara sosial yang melibatkan keluarga. Seseorang mungkin merasa harus "berakting" sempurna untuk menghindari pertanyaan atau komentar yang tidak nyaman.
                            </p>
                        </div>
                        <div>
                            <h3 class="font-medium text-lg text-gray-600 mb-2">2. Merasa Tidak Berharga</h3>
                            <p>
                                Saat gagal memenuhi ekspektasi, seseorang bisa mulai meragukan diri sendiri dan merasa bahwa mereka tidak cukup baik. Ini dapat merusak harga diri dan menimbulkan perasaan sedih atau depresi.
                            </p>
                        </div>
                        <div>
                            <h3 class="font-medium text-lg text-gray-600 mb-2">3. Isolasi Sosial</h3>
                            <p>
                                Daripada menghadapi tekanan, banyak orang memilih untuk mengisolasi diri. Mereka menghindari acara keluarga atau sosial, yang pada akhirnya justru memperparah perasaan kesepian dan terasing.
                            </p>
                        </div>
                        <div>
                            <h3 class="font-medium text-lg text-gray-600 mb-2">4. Konflik Internal</h3>
                            <p>
                                Tekanan sosial bisa menciptakan konflik antara keinginan diri sendiri dan ekspektasi orang lain. Hal ini menyebabkan kebingungan identitas dan kesulitan untuk menjadi diri sendiri.
                            </p>
                        </div>
                    </div>
                </section>

                <!-- Bagian 3: Solusi Rent A Family -->
                <section class="text-section mb-12">
                    <h2 class="text-2xl md:text-3xl font-semibold text-indigo-700 mb-4">"Rent A Family": Solusi Profesional</h2>
                    <p>
                        Di tengah tekanan ini, "Rent A Family" hadir bukan untuk menggantikan keluarga Anda, melainkan sebagai solusi sementara yang profesional untuk mengatasi momen-momen sulit. Kami menawarkan dukungan yang aman dan bebas konflik, sehingga Anda bisa menghadiri acara penting tanpa beban.
                    </p>
                    <div class="mt-6 flex flex-col md:flex-row items-center space-y-4 md:space-y-0 md:space-x-4">
                        <a href="#" id="learn-more-btn" class="btn-primary w-full md:w-auto px-6 py-3 text-lg font-semibold text-white bg-blue-600 rounded-lg shadow-lg hover:bg-blue-700 text-center">
                            Pelajari Layanan Kami
                        </a>
                        <a href="#" class="btn-primary w-full md:w-auto px-6 py-3 text-lg font-semibold text-blue-600 border-2 border-blue-600 rounded-lg hover:bg-blue-50 text-center">
                            Baca Kisah Sukses Klien
                        </a>
                    </div>
                </section>
            </main>

            <!-- Footer -->
            <footer class="text-center py-6 px-4 text-gray-500 text-sm">
                <p>&copy; 2024 Rent A Family. Semua Hak Cipta Dilindungi.</p>
            </footer>
        </div>

        <!-- Halaman Layanan/Formulir Pemesanan (Awalnya tersembunyi) -->
        <div id="service-page" class="hidden">
            <!-- Konten Layanan dari prototipe sebelumnya -->
            <header class="text-center mb-10">
                <h1 class="text-3xl md:text-4xl font-extrabold text-gray-800 mb-2">Layanan Rent A Family</h1>
                <p class="text-gray-500 text-lg">Pesan kehadiran keluarga sementara Anda untuk momen spesial.</p>
            </header>

            <section class="mb-10">
                <h2 class="text-2xl font-bold text-gray-700 mb-4">Solusi Profesional untuk Kebutuhan Anda</h2>
                <p class="text-gray-600 leading-relaxed mb-4">
                    "Rent A Family" hadir sebagai solusi profesional bagi Anda yang membutuhkan kehadiran figur keluarga dalam acara penting. Kami menyediakan "aktor" terlatih untuk memberikan dukungan emosional dan kenyamanan sosial, memastikan Anda tampil "sempurna" tanpa tekanan atau konflik emosional.
                </p>
                <p class="text-gray-600 leading-relaxed">
                    Ini adalah prototipe sederhana dari paket layanan utama kami, yang dirancang untuk memvalidasi alur pemesanan dan pengalaman pengguna.
                </p>
            </section>

            <section>
                <h2 class="text-2xl font-bold text-gray-700 mb-4">Pesan Layanan Anda</h2>
                <form id="orderForm" class="space-y-6">
                    <div>
                        <label for="nama" class="block text-sm font-medium text-gray-700">Nama Lengkap</label>
                        <input type="text" id="nama" name="nama" class="mt-1 block w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500" required>
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                        <input type="email" id="email" name="email" class="mt-1 block w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500" required>
                    </div>
                    <div>
                        <label for="usia" class="block text-sm font-medium text-gray-700">Usia</label>
                        <input type="number" id="usia" name="usia" min="18" class="mt-1 block w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500" required>
                    </div>
                    <div>
                        <label for="tanggal_acara" class="block text-sm font-medium text-gray-700">Tanggal Acara</label>
                        <input type="date" id="tanggal_acara" name="tanggal_acara" class="mt-1 block w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500" required>
                    </div>
                    <div>
                        <label for="paket" class="block text-sm font-medium text-gray-700">Pilih Paket Layanan</label>
                        <select id="paket" name="paket" class="mt-1 block w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500" required>
                            <option value="">-- Pilih Paket --</option>
                            <option value="pasangan">Pasangan</option>
                            <option value="orang_tua">Orang Tua</option>
                            <option value="saudara_kandung">Saudara Kandung</option>
                            <option value="kakek_nenek">Kakek-Nenek</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">Jenis Pertemuan</label>
                        <div class="flex items-center space-x-4">
                            <label class="inline-flex items-center">
                                <input type="radio" name="jenis_pertemuan" value="online" class="form-radio text-blue-600" checked>
                                <span class="ml-2 text-gray-700">Konsultasi Online (via Zoom)</span>
                            </label>
                            <label class="inline-flex items-center">
                                <input type="radio" name="jenis_pertemuan" value="langsung" class="form-radio text-blue-600">
                                <span class="ml-2 text-gray-700">Bertemu Langsung di Tempat</span>
                            </label>
                        </div>
                    </div>
                    <div id="alamat-group" class="hidden">
                        <label for="alamat" class="block text-sm font-medium text-gray-700">Alamat Acara</label>
                        <textarea id="alamat" name="alamat" rows="3" class="mt-1 block w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500" placeholder="Masukkan alamat lengkap acara Anda"></textarea>
                    </div>
                    <div>
                        <label for="pesan" class="block text-sm font-medium text-gray-700">Pesan & Detail Tambahan</label>
                        <textarea id="pesan" name="pesan" rows="4" class="mt-1 block w-full px-4 py-2 bg-gray-100 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500" placeholder="Contoh: Pernikahan, Mohon hadir sebagai orang tua mempelai wanita."></textarea>
                    </div>
                    <button type="submit" class="w-full py-3 px-4 rounded-md shadow-lg font-semibold text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 transition-colors">
                        Pesan Paket Ini
                    </button>
                </form>
            </section>

            <div id="confirmation-modal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center p-4 hidden">
                <div class="bg-white p-8 rounded-lg shadow-xl max-w-sm w-full text-center">
                    <div class="mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-green-500 mx-auto" viewBox="0 0 20 20" fill="currentColor">
                            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                        </svg>
                    </div>
                    <h4 class="text-2xl font-bold text-gray-800 mb-2">Terima Kasih!</h4>
                    <p class="text-gray-600 mb-4">Pesanan Anda telah kami terima. Tim kami akan segera menghubungi Anda untuk menjadwalkan konsultasi.</p>
                    <button id="close-modal-btn" class="bg-blue-600 text-white font-semibold px-4 py-2 rounded-md hover:bg-blue-700 transition-colors">
                        Tutup
                    </button>
                </div>
            </div>
            
            <button id="back-to-edu-btn" class="mt-8 mx-auto block px-6 py-3 text-lg font-semibold text-gray-600 border-2 border-gray-300 rounded-lg hover:bg-gray-100 text-center">
                Kembali ke Halaman Edukasi
            </button>
        </div>
    </div>

    <script>
        // Mengambil elemen-elemen utama
        const eduPage = document.getElementById('edu-page');
        const servicePage = document.getElementById('service-page');
        const learnMoreBtn = document.getElementById('learn-more-btn');
        const backToEduBtn = document.getElementById('back-to-edu-btn');
        
        // Logika untuk beralih halaman
        function showServicePage() {
            eduPage.classList.add('hidden');
            servicePage.classList.remove('hidden');
        }

        function showEduPage() {
            servicePage.classList.add('hidden');
            eduPage.classList.remove('hidden');
        }

        // Menambahkan event listener untuk tombol-tombol
        learnMoreBtn.addEventListener('click', function(event) {
            event.preventDefault();
            showServicePage();
        });

        backToEduBtn.addEventListener('click', function(event) {
            event.preventDefault();
            showEduPage();
        });

        // Bagian JavaScript untuk form pemesanan (sudah ada sebelumnya)
        const form = document.getElementById('orderForm');
        const modal = document.getElementById('confirmation-modal');
        const closeModalBtn = document.getElementById('close-modal-btn');
        const jenisPertemuanRadios = document.getElementsByName('jenis_pertemuan');
        const alamatGroup = document.getElementById('alamat-group');
        const alamatInput = document.getElementById('alamat');

        function toggleAlamatInput() {
            if (document.querySelector('input[name="jenis_pertemuan"]:checked').value === 'langsung') {
                alamatGroup.classList.remove('hidden');
                alamatInput.setAttribute('required', 'required');
            } else {
                alamatGroup.classList.add('hidden');
                alamatInput.removeAttribute('required');
            }
        }

        jenisPertemuanRadios.forEach(radio => {
            radio.addEventListener('change', toggleAlamatInput);
        });

        form.addEventListener('submit', function(event) {
            event.preventDefault();
            modal.classList.remove('hidden');
            form.reset();
        });

        closeModalBtn.addEventListener('click', function() {
            modal.classList.add('hidden');
        });

        modal.addEventListener('click', function(event) {
            if (event.target === modal) {
                modal.classList.add('hidden');
            }
        });

        toggleAlamatInput();
    </script>

</body>
</html>
