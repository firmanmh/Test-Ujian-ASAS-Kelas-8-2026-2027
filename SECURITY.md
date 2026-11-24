---

### 2. `SECURITY.md`

Salin kode di bawah ini dan simpan sebagai **`SECURITY.md`** di folder utama repositori Anda untuk menjelaskan standar privasi dan keamanan aplikasi kepada pengguna maupun kontributor:

```markdown
# Kebijakan Keamanan (Security Policy)

## Versi yang Didukung

Pembaruan keamanan dan perbaikan bug diterapkan pada versi berikut:

| Versi | Status Dukungan |
| :--- | :--- |
| `1.x` (`main`) | ✅ Didukung aktif |
| `< 1.0` | ❌ Tidak didukung |

---

## Arsitektur Keamanan & Privasi Data Siswa

Aplikasi **Modul Visual & Latihan Interaktif — Informatika SMP Kelas IX** dirancang khusus agar aman digunakan oleh pelajar:

- **100% Client-Side (Sisi Klien):** Seluruh logika simulasi, generator soal acak, dan penilaian berjalan langsung di browser pengguna tanpa mengirim data ke server eksternal.
- **Tanpa Pengumpulan Data Pribadi:** Aplikasi tidak meminta, menyimpan, maupun mengirimkan nama lengkap, NISN, alamat email, kata sandi, atau skor latihan siswa ke pihak ketiga.
- **Tanpa Cookies & Pelacak:** Tidak menggunakan *tracking cookies*, analitik pihak ketiga, maupun penyimpanan persisten yang melacak aktivitas siswa.
- **Sumber Daya Eksternal Minimal:** Hanya memuat font resmi dari Google Fonts (`fonts.googleapis.com` dan `fonts.gstatic.com`) melalui koneksi terenkripsi HTTPS.

---

## Melaporkan Kerentanan Keamanan

Jika Anda menemukan potensi masalah keamanan—seperti celah *Cross-Site Scripting (XSS)* saat kustomisasi konten, tautan eksternal yang tidak aman, atau masalah integritas kode—harap laporkan secara bertanggung jawab:

1. Buka tab **Security** > **Advisories** pada repositori GitHub ini dan klik **Report a vulnerability** (jika fitur *Private Vulnerability Reporting* aktif).
2. Jika fitur tersebut tidak tersedia, buat laporan melalui tab **Issues** dengan menyertakan:
   - Deskripsi singkat masalah yang ditemukan.
   - Langkah-langkah untuk mereproduksi masalah (*steps to reproduce*).
   - Saran perbaikan (jika ada).

Laporan akan ditinjau sesegera mungkin dan pembaruan akan dirilis pada cabang `main`.

---

## Rekomendasi Hosting Aman

Apabila sekolah atau guru menghosting modul ini secara daring untuk diakses siswa:
- Pastikan situs disajikan melalui protokol **HTTPS** (misalnya menggunakan GitHub Pages, Netlify, atau Vercel).
- Hindari menyisipkan skrip pelacak atau iklan pihak ketiga ke dalam file `index.html`.
