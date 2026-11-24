# 📘 Modul Visual & Latihan Interaktif — Informatika SMP Kelas IX

Aplikasi web pembelajaran mandiri berbasis HTML tunggal (*single-file web app*) untuk mata pelajaran **Informatika Kelas IX SMP (Semester 1)**. Modul ini dirancang dengan tampilan bersih dan modern bergaya **Astra 6 Pro** serta dilengkapi ilustrasi animasi SVG dan simulator praktik langsung tanpa memerlukan koneksi backend maupun instalasi rumit.

---

## ✨ Fitur Utama & Cakupan Materi

### 🎨 Antarmuka Modern (Astra 6 Pro UI)
- **Sticky Glassmorphism Header & Reading Progress Bar:** Navigasi cepat antar-bab dengan indikator progres membaca otomatis di bagian atas layar.
- **Tipografi & Tata Letak Responsif:** Menggunakan kombinasi font *Plus Jakarta Sans* dan *Inter* yang nyaman dibaca di layar ponsel maupun laptop.
- **Zero-Dependency:** Berjalan 100% menggunakan HTML5, CSS3, dan Vanilla JavaScript dalam satu file (`index.html`).

### 🧮 Bab 1: Sistem Bilangan & Teknik Perhitungan Unplugged
- **Tabel Referensi Basis Bilangan:** Ringkasan Desimal (Basis 10), Biner (Basis 2), Oktal (Basis 8), dan Heksadesimal (Basis 16).
- **Simulasi Kartu Titik Biner Interaktif:** Kartu visual kelipatan dua (`16, 8, 4, 2, 1`) yang dapat diklik untuk membuka/menutup titik dan melihat hasil konversi secara langsung.
- **Diagram Animasi SVG:** Visualisasi langkah pembagian berulang dan pembobotan perpangkatan.
- **Tes Konversi Bilangan Acak:** Generator soal otomatis tanpa batas untuk latihan konversi antar-basis lengkap dengan pembahasan jawaban.

### 🤖 Bab 2: Algoritma & Pemrograman Dasar Scratch
- **Diagram Animasi Rute Grid & Antarmuka Scratch:** Penjelasan visual algoritma berurutan (*sequence*) dan struktur blok kode Scratch.
- **Pelatihan 2A — Simulator Robot Grid 5×5:** Siswa menyusun antrean blok perintah (*Maju*, *Putar Kiri*, *Putar Kanan*) untuk mengarahkan robot dari `START` menuju `FINISH` tanpa menabrak rintangan batu.
- **Pelatihan 2B — Simulator 3 Misi Scratch:** Latihan menyusun blok kode (*Events*, *Control*, *Motion*, *Sensing*, *Looks*) dengan animasi panggung (*Stage*) untuk tingkat Mudah, Menengah, dan Sulit.

### 🛡️ Bab 3: Keamanan Data Pribadi & Anti-Cyberbullying
- **Infografis Animasi Edukasi:** Visualisasi pencegahan *phishing*, pembuatan *password* kuat, aktivasi Autentikasi Dua Faktor (2FA), serta literasi *Interland Google*.
- **Tes Pencocokan Tarik Benang:** Kuis interaktif menghubungkan 5 pasangan kasus keamanan digital dan anti-*cyberbullying* secara acak dari 10 bank soal.

---

## 📂 Struktur File

```text
├── index.html      # File utama modul pembelajaran & seluruh logika interaktif
├── README.md       # Dokumentasi proyek
└── SECURITY.md     # Kebijakan keamanan dan privasi aplikasi
