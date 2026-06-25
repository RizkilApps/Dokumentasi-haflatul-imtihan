⚡ Galeri Haflatul Imtihan — SMK An-Nur Karomatul Hasan ⚡

Portal galeri dokumentasi pintar berbasis cloud yang mengintegrasikan Google Drive secara langsung ke dalam halaman web interaktif tanpa memerlukan basis data (database) terpisah. Dibangun dengan gaya desain Neo Brutalism yang tebal, berani, serta ramah pengguna.

✨ Fitur-Fitur Unggulan

🟥🟨 Desain Neo Brutalism Merah & Kuning: Tampilan estetis yang mencolok dengan garis border tebal, bayangan tegas, dan warna kontras tinggi.

☁️ Cloud Database Otomatis (Serverless): Tidak perlu mengunggah foto satu-per-satu lewat website. Website akan melakukan sinkronisasi otomatis (Live-Sync) langsung dari folder Google Drive Anda.

🎥 Mendukung Gambar & Pemutar Video: Galeri pintar otomatis mendeteksi apakah file yang diunggah berupa gambar (.jpg/.png/.webp) atau video (.mp4/.mov). Pemutar video interaktif tertanam langsung di dalam modal.

⚡ Performa Kilat (Zero-Delay Loading): Menggunakan optimasi native lazy loading dari HTML5 modern agar performa halaman web tetap gegas dan menghemat kuota internet pengunjung.

🚀 Fitur Berkelas Produksi:

Pencarian realtime responsif berdasarkan nama file.

Penyaringan instan berdasarkan kategori (Guru, Siswa, VIP).

Statistik media dinamis dengan animasi penambahan angka.

Infinite Scroll & Tombol Scroll to Top.

Sistem unduhan langsung (Direct Auto-Download) otomatis tanpa hambatan CORS browser.

📁 Struktur Penyimpanan Google Drive

Agar sistem API berjalan dengan baik, pastikan Anda membuat struktur folder di Google Drive Anda persis seperti berikut:

Galeri Haflatul Imtihan (ID Folder Utama)
│
├── Guru  ──> Tempat foto & video dokumentasi asatidz/guru
├── Siswa ──> Tempat foto & video santri/siswa & pentas seni
└── VIP   ──> Tempat foto & video penyambutan kyai/tokoh penting


Catatan Keamanan: Pastikan folder utama Galeri Haflatul Imtihan telah diubah izin aksesnya (Share) menjadi "Anyone with the link" (Siapa saja yang memiliki link) sebagai Pengakses Lihat-Saja (Viewer) agar aset media dapat dimuat dengan lancar di website.

🛠️ Langkah Cepat Pengaktifan Sistem Cloud

1. Sisi Server (Google Apps Script)

Buka Google Apps Script.

Buat proyek kosong baru.

Ganti kode bawaan dengan script API versi Gambar & Video teroptimasi (bisa Anda salin dari histori chat Anda).

Masukkan ID Folder Utama Google Drive Anda pada bagian const PARENT_FOLDER_ID = "...".

Klik Deploy -> New Deployment.

Pilih jenis konfigurasi sebagai Web App.

Atur akses:

Execute as: Me (Akun Google Anda)

Who has access: Anyone (Siapa saja)

Klik Deploy, izinkan akses keamanan (Authorize Access), lalu salin Web app URL yang diperoleh.

2. Sisi Klien (Frontend Website)

Buka berkas index.html.

Temukan variabel GOOGLE_SCRIPT_API_URL (terletak pada bagian paling atas tag <script> JavaScript).

Tempelkan URL Web App yang telah Anda salin sebelumnya:

const GOOGLE_SCRIPT_API_URL = "https://script.google.com/macros/s/AKfycb.../exec";


Simpan berkas, luncurkan website Anda, dan saksikan keajaiban otomatisasinya!

🚀 Teknologi yang Digunakan

HTML5 & CSS3 (Kustom Arsitektur Neo Brutalism)

Bootstrap v5.3 (Tata Letak Tata Ruang / Grid & Modal Lightbox)

Bootstrap Icons (Kumpulan Font Simbol Interaktif)

Vanilla JavaScript (Logika Frontend, Manipulasi DOM, & Integrasi API Fetch)

Google Apps Script & Drive API (Penyimpanan Cloud Awan Terdesentralisasi)

📜 Lisensi & Hak Cipta

Copyright © 2026 SMK AN-NUR KAROMATUL HASAN. Hak Cipta Dilindungi Undang-Undang.

Sistem diintegrasikan langsung menggunakan infrastruktur mandiri Google Cloud Platform.
