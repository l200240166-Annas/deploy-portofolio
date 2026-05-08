# Laporan Proyek Pemrograman Web - Portofolio Personal (L200240166-Annas)

## 1. Deskripsi Proyek

Proyek ini adalah sebuah website portofolio personal yang dirancang untuk menampilkan profil, karya, dan informasi kontak secara profesional. Website ini mengusung desain modern, bersih, dan mendukung fitur mode gelap (dark mode) untuk kenyamanan pengguna.

**Tujuan**: Memperkenalkan profil diri sebagai mahasiswa Teknik Informatika serta memamerkan keahlian dalam pengembangan web dasar (HTML, CSS, dan JavaScript).

**Fitur Utama**:

- **5 Halaman Utama**: Yaitu contact.html, index.html, Portofolio.html, style.css, dan pavicon.ico
- **Hero Section**: Tampilan utama yang berani dengan tipografi besar dan foto profil.
- **Dark Mode**: Fitur perpindahan tema (Terang/Gelap) menggunakan local storage.
- **Portfolio Grid**: Menampilkan daftar proyek (Website Biodata, Desain Poster, JavaScript Logic) menggunakan sistem  grid yang responsif.
- **Contact Form**: Formulir kontak fungsional yang terintegrasi dengan Formspree.
- **Interactive Motto**: Tombol interaktif (ikon kucing) untuk menampilkan modal motto hidup.

**Teknologi yang Digunakan**:

- **HTML5**: Struktur semantik yang sudah dibersihkan dari _trailing slashes_ agar sesuai standar W3C.
- **Tailwind CSS**: Framework CSS utama untuk styling yang cepat dan responsif melalui CDN.
- **Font Awesome**: Digunakan untuk ikon-ikon sosial media dan navigasi.
- **Google Fonts**: Menggunakan font "Inter" untuk tampilan tipografi yang modern.

## 2. Struktur Folder dan File

membangun-website-personal-I200240166-Annas-1/
├── assets/
├   ├── favicon.ico
│   ├── lighthouse.png
│   ├── ssh.png
│   ├── validasi-contact.png
│   ├── validasi-css.png
│   ├── validasi-index.png
│   └── validasi-portofolio.png
├── images/
│   └── foto.jpg
├── contact.html
├── index.html
├── LAPORAN.md
├── portofolio.html
└── style.css

## 3. Link Website yang sudah di host/ deployment



## 4. Cek Validasi

**Hasil Validasi W3C (HTML & CSS)**

![Validasi Index](assets/validasi-index.png)  
![Validasi Portofolio](assets/validasi-portofolio.png)
![Validasi Contact](assets/validasi-contact.png)
![Validasi CSS](assets/validasi-css.png)

**Skor Lighthouse (Bonus)**
![Skor Lighthouse](assets/lighthouse.png)

**Bukti Push ke GitHub (SSH)**
![Bukti SSH](assets/ssh.png)

## 5. Catatan Pengembangan
Dalam proses pembuatan portofolio personal ini, berikut adalah beberapa poin teknis dan catatan pengembangan yang dilakukan:

**Teknologi yang Digunakan:**
  -HTML5: Digunakan untuk struktur semantik (menggunakan tag <header>, <main>, <footer>, dll).
  -CSS3: Digunakan untuk styling manual tanpa framework (Pure CSS), termasuk Flexbox untuk tata letak yang responsif.
  -Metodologi: Menerapkan prinsip Clean Code agar struktur folder dan penamaan class mudah dibaca.

**Proses Pengerjaan:**
  -Perancangan Struktur: Membuat kerangka HTML untuk halaman Index, Portofolio, dan Contact.
  -Styling & Responsivitas: Menambahkan Media Queries agar tampilan tetap rapi saat dibuka di perangkat mobile.
  -Optimasi: Melakukan kompresi pada aset gambar agar loading speed website lebih cepat (terbukti dengan skor -Lighthouse yang baik).
  -Validasi: Memastikan seluruh kode memenuhi standar W3C agar tidak ada error sintaks.

**Kendala dan Solusi:**
  -Kendala: Kesulitan dalam mengatur posisi elemen pada form kontak agar presisi.
  -Solusi: Menggunakan properti box-sizing: border-box; dan Flexbox untuk mengatur jarak antar elemen secara otomatis.

**Fitur Utama:**
  -Navigasi yang responsif.
  -Formulir kontak yang sudah tervalidasi secara HTML5.
  -Galeri proyek yang tertata rapi.
