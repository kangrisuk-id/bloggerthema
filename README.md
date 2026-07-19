# DevSpace Minimal (v3) 🚀

[![Platform](https://img.shields.io/badge/Platform-Blogger-orange.svg)](https://www.blogger.com)
[![License](https://img.shields.io/badge/License-Non--Commercial-blue.svg)](#license)
[![Theme-Style](https://img.shields.io/badge/Theme-Dark%20Mode-slate.svg)](#features)

![Preview Tema](https://raw.githubusercontent.com/kangrisuk-id/bloggerthema/main/img/DevSpace%20Minimal.png)

**DevSpace Minimal** adalah template Blogger premium bertema gelap (*dark mode*) yang dirancang khusus untuk para pengembang perangkat lunak (*software engineers*), blogger teknis, dan antusias *open-source*. Template ini menggabungkan kesederhanaan, kecepatan, dan estetika futuristik tanpa mengorbankan keterbacaan kode pemrograman.

Situs web ini dioperasikan sepenuhnya untuk tujuan **non-komersial**, edukasi, dan dokumentasi portofolio pribadi.

---

## ✨ Fitur Unggulan

- **Matrix Code Particles Background:** Efek latar belakang dinamis interaktif yang menampilkan simbol sintaksis (`0`, `1`, `{`, `}`, `[]`, `=>`) berbasis HTML5 Canvas murni. Sangat ringan dan berjalan secara asinkronus tanpa membebani performa CPU/baterai.
- **Glassmorphism UI / Frosted Glass:** Kartu postingan menggunakan efek buram transparan (`backdrop-filter`) tingkat lanjut untuk memastikan teks artikel tetap kontras dan nyaman dibaca di atas partikel yang bergerak.
- **Smart 2-Column Grid Layout:** Sistem tata letak adaptif yang otomatis menyusun tumpukan artikel panjang menjadi kisi kartu berdampingan. Postingan terbaru secara cerdas mengambil ukuran penuh (*full-width*) sebagai sorotan utama.
- **Automated Text Snippet:** Halaman depan otomatis memotong teks artikel panjang secara rapi (maksimal 3 baris) menggunakan optimasi CSS `-webkit-line-clamp`, menjaga halaman utama tetap ringkas dan elegan.
- **Syntax Friendly Boilerplate:** Tag bawaan `<pre><code>` telah dikonfigurasi secara visual agar serasi dengan skema warna teks editor populer seperti VS Code atau JetBrains.
- **Zero Third-Party Dependencies:** Dibangun murni menggunakan CSS dan Vanilla JS modern tanpa jQuery atau Bootstrap, menghasilkan pemuatan halaman yang instan.

---

## 🛠️ Panduan Instalasi

Ikuti langkah-langkah berikut untuk memasang tema pada blog Anda:

### 1. Salin Kode Source
Dapatkan berkas template resmi bertema partikel berkode langsung dari repositori ini:
➡️ [Unduh Kode XML Resmi Di Sini](https://github.com/kangrisuk-id/bloggerthema/blob/main/template/DevSpaceMinimal.xml)

### 2. Terapkan ke Blogger
1. Masuk ke dasbor [Blogger](https://www.blogger.com/).
2. Pada menu navigasi kiri, pilih **Tema (Theme)**.
3. Klik ikon panah kecil ke bawah di sebelah tombol **Sesuaikan (Customize)**, lalu pilih **Edit HTML**.
4. Hapus seluruh baris kode lama di dalam editor tersebut, lalu tempel (*paste*) kode XML `DevSpaceMinimal.xml` yang telah Anda salin sebelumnya.
5. Klik ikon **Simpan (Save)** di pojok kanan atas.

### 3. Konfigurasi Navigasi Halaman Statis
Setelah tema terpasang, cari baris kode `<nav class='nav-links'>` (sekitar baris 124-129) di dalam Editor HTML Blogger Anda, lalu sesuaikan URL tautan berikut dengan tautan halaman resmi blog Anda:

```html
<nav class='nav-links'>
    <a expr:href='data:blog.homepageUrl'>Home</a>
    <a href='[https://URL-BLOG-ANDA.blogspot.com/p/koleksi.html](https://URL-BLOG-ANDA.blogspot.com/p/koleksi.html)'>Koleksi</a>
    <a href='[https://URL-BLOG-ANDA.blogspot.com/p/about.html](https://URL-BLOG-ANDA.blogspot.com/p/about.html)'>About</a>
    <a href='[https://URL-BLOG-ANDA.blogspot.com/p/privacy-policy.html](https://URL-BLOG-ANDA.blogspot.com/p/privacy-policy.html)'>Privacy Policy</a>
    <a href='[https://URL-BLOG-ANDA.blogspot.com/p/terms-of-service.html](https://URL-BLOG-ANDA.blogspot.com/p/terms-of-service.html)'>TOS</a>
</nav>
