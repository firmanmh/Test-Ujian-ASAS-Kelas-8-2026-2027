📝 Portal Ujian Informatika Kelas VIII SMP

Repositori ini merupakan halaman pembungkus (wrapper) berbasis GitHub Pages yang dirancang untuk menjaga integritas dan ketertiban pelaksanaan evaluasi daring Informatika Kelas VIII menggunakan Google Formulir dan Form Presenter + Timer.

✨ Fitur Utama Sistem Ujian

Auto-Refresh & Reset Jawaban Anti-Curang (index.html)

Secara otomatis mendeteksi apabila peserta ujian menutup browser, menekan tombol Home, membagi layar (split-screen), berpindah tab, atau membuka aplikasi lain (visibilitychange & window.blur).

Halaman otomatis dimuat ulang dari awal sehingga pilihan jawaban yang belum dikirim akan terhapus.

Batas Waktu 120 Menit & Auto-Submit (Form Presenter + Timer)

Penghitung waktu mundur otomatis selama 120 menit (2 jam).

Jika waktu habis (00:00:00), formulir otomatis terkirim (auto-submit) dan menutup akses pengerjaan.

Pembatasan 1 Email = 1 Kali Mengerjakan

Menggunakan verifikasi akun Google resmi sehingga setiap siswa hanya dapat mengirimkan jawaban satu kali.

Penilaian & Skor Akhir Otomatis

Terdiri dari 50 soal Pilihan Ganda (level kognitif C1, C2, dan C3) dengan bobot 2 poin per soal (skor maksimal 100) yang langsung muncul setelah jawaban terkirim.

📂 Struktur File Repositori

├── index.html      # Halaman utama pembungkus ujian (deteksi pindah tab & auto-refresh)
└── README.md       # Dokumentasi panduan pengaturan dan penggunaan repositori


⚙️ Panduan Pengaturan (Untuk Guru / Admin)

1. Pengaturan Google Formulir

Buka Google Formulir ujian Anda, masuk ke tab Setelan (Settings), lalu pastikan opsi berikut aktif:

Jadikan ini sebagai kuis: Aktifkan → Rilis nilai: Segera setelah setiap pengiriman → Centang Nilai poin.

Jawaban (Responses):

Kumpulkan alamat email: Terverifikasi (Verified).

Aktifkan Batasi ke 1 jawaban (Limit to 1 response).

Nonaktifkan Edit setelah pengiriman.

Presentasi (Presentation):

Aktifkan Nonaktifkan simpan otomatis untuk semua responden (Disable autosave for all respondents) agar fitur auto-refresh menghapus draf jawaban sementara dengan bersih.

2. Pengaturan Add-on Form Presenter + Timer

Buka menu Add-on (ikon Puzzle) di Google Formulir → pilih Form Presenter + Timer → klik Setup.

Atur Time Limit menjadi 120 menit.

Aktifkan opsi Auto Submit on Time Out.

Klik Publish Form, lalu salin tautan ujian yang diberikan oleh Form Presenter.

3. Menghubungkan Tautan ke index.html

Buka file index.html di repositori GitHub ini, lalu klik ikon Edit (pensil).

Cari baris kode berikut:

<iframe 
  id="examFrame" 
  src="PASTE_LINK_FORM_PRESENTER_DI_SINI" 
  allow="camera; microphone; fullscreen">


Ganti tulisan PASTE_LINK_FORM_PRESENTER_DI_SINI dengan tautan yang sudah disalin dari Form Presenter + Timer.

Klik Commit changes... untuk menyimpan perubahan.

4. Mengaktifkan GitHub Pages

Masuk ke tab Settings pada repositori ini → pilih menu Pages di bilah kiri.

Pada bagian Build and deployment → Branch, pilih main dan folder / (root), lalu klik Save.

Tunggu 1–2 menit hingga tautan situs aktif muncul di bagian atas halaman (format: https://<username>.github.io/<nama-repositori>/).

📋 Tata Tertib untuk Peserta Ujian (Siswa)

Pastikan sudah login ke akun Google masing-masing di aplikasi browser (Google Chrome) sebelum membuka tautan ujian.

Gunakan satu perangkat (HP atau laptop) secara penuh dan jangan mengaktifkan mode layar terbagi (split-screen).

Dilarang keluar dari halaman ujian, berpindah tab, atau membuka aplikasi lain selama tes berlangsung karena sistem akan otomatis memuat ulang halaman dan menghapus jawaban yang belum terkirim.

Perhatikan sisa waktu (120 menit) di bagian atas layar. Sistem akan mengirimkan jawaban secara otomatis apabila waktu berakhir.

📚 Cakupan Materi Evaluasi (Informatika Kelas VIII)

Bab 1: Aplikasi Pengolah Kata (Word Processor), Antarmuka Dokumen, Pintasan Keyboard, dan Manajemen Clipboard.

Bab 2: Manajemen File & Folder Lintas Platform (Laptop, HP, Cloud Storage) serta Klasifikasi Ekstensi Berkas.

Bab 3: Komponen Sistem Komputer (Hardware, Software, Brainware) dan Siklus Operasi CPU (Fetch – Decode – Execute – Store).
