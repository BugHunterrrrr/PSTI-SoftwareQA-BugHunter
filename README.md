<div align="center">

# 🚀 PSTI - Software Quality Assurance 🚀
### Project Laporan Pengujian - Kelompok Bug Hunter

</div>

> Proyek ini berfokus pada pengujian jaminan kualitas perangkat lunak (Software Quality Assurance) untuk **Panel Admin Koperasi Mahasiswa Universitas Lampung**. Repositori ini berisi dokumentasi, skenario pengujian, dan panduan penggunaan alat yang dapat anda manfaatkan.

<div align="center">

![Status](https://img.shields.io/badge/Status-Selesai-green)
![Pengujian](https://img.shields.io/badge/Alat-Selenium%20IDE-orange)
![Platform](https://img.shields.io/badge/Platform-Web-blue)

</div>

---

## 👥 Tim Kami: Bug Hunter

Berikut adalah anggota kelompok yang berkontribusi dalam proyek ini:

| Peran | Nama | NPM |
| :--- | :--- | :--- |
| 👨‍💻 **Ketua** | Ahmad Fairuz Rizky Gani | 2215061029 |
| 👨‍💻 **Anggota** | Andreas Pujo Santoso | 2215061101 |
| 👨‍💻 **Anggota** | Harry Bonardo Situmorang | 2215061089 |
| 👨‍💻 **Anggota** | Reza Rafli Fahlendi | 2215061049 |

---

## 🎯 Aplikasi yang Diuji

* **Nama Website:** Panel Koperasi Mahasiswa Universitas Lampung
* **URL Target:** [**https://kopmaunila.com/panel**](https://kopmaunila.com/panel)

---

## 🎥 Video Presentasi Proyek

Untuk penjelasan lebih detail dan demonstrasi langsung mengenai proses pengujian, silakan tonton video presentasi kami di YouTube dengan mengklik gambar di bawah ini.

<a href="https://www.youtube.com/watch?v=VIDEO_ID_ANDA" target="_blank">
  <img src="https://img.youtube.com" alt="Link Presentasi Video Proyek" style="width:100%;">
</a>

---

## 🛠️ Panduan Pengujian dengan Selenium IDE

<details>
<summary>
  <strong>Klik di sini untuk melihat panduan lengkap penggunaan Selenium IDE</strong>
</summary>

<br>

Pengujian ini dilakukan secara otomatis menggunakan **Selenium IDE**, sebuah ekstensi browser yang sangat berguna. Berikut adalah panduan langkah demi langkah tentang cara anda menggunakannya.

### 1️⃣ **Instalasi**
Langkah pertama adalah menambahkan ekstensi Selenium IDE ke browser anda.

* [**Selenium IDE untuk Google Chrome**](https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd)
* [**Selenium IDE untuk Mozilla Firefox**](https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/)

Setelah terinstal, ikon Selenium IDE akan muncul di toolbar browser anda.

### 2️⃣ **Merekam Skenario Pengujian (Test Case)**
Cara termudah untuk membuat pengujian adalah dengan merekam interaksi anda.

1.  **Buka Selenium IDE**: Klik ikonnya di toolbar browser.
2.  **Buat Proyek Baru**: Pilih "**Create a new project**" dan beri nama proyek anda (contoh: `Pengujian_Kopma_Unila`).
3.  **Atur Base URL**: Masukkan URL target `https://kopmaunila.com/panel` lalu klik "**START RECORDING**".
4.  **Lakukan Aksi**: Sebuah jendela browser baru akan terbuka. Lakukan aksi yang ingin anda uji (misalnya, proses login dengan mengisi username, password, dan menekan tombol masuk).
5.  **Hentikan Perekaman**: Jika selesai, kembali ke jendela Selenium IDE dan klik tombol merah "**Stop Recording**".
6.  **Beri Nama Test Case**: Beri nama yang deskriptif untuk pengujian anda (contoh: `Skenario_Login_Berhasil`).

### 3️⃣ **Menambahkan Validasi (Assertions)**
Pengujian tidak lengkap tanpa validasi untuk memastikan hasilnya sesuai harapan.

1.  Setelah merekam login, anda bisa memeriksa apakah anda benar-benar masuk ke halaman dashboard.
2.  Pada halaman web, **klik kanan** pada elemen yang ingin anda validasi (misalnya, tulisan "Dashboard").
3.  Dari menu, pilih **Selenium IDE > Assert > text**. Perintah ini akan memvalidasi bahwa elemen tersebut mengandung teks yang benar.
4.  Anda juga bisa menambahkan perintah secara manual seperti `assert element present` untuk memastikan sebuah elemen (misalnya logo atau menu) muncul setelah login.

### 4️⃣ **Menyimpan dan Menjalankan Ulang Pengujian**
1.  **Simpan Proyek**: Klik ikon **simpan (save)** di pojok kanan atas untuk menyimpan seluruh pekerjaan anda dalam sebuah file `.side`.
2.  **Jalankan Pengujian**: Pilih skenario dari panel kiri, lalu klik tombol "**Run Current Test**" (ikon ▶).
3.  **Analisis Hasil**: Perhatikan panel **Log** di bagian bawah.
    * <span style="color:green;">**Hijau**</span> menandakan langkah berhasil.
    * <span style="color:red;">**Merah**</span> menandakan langkah gagal atau bug ditemukan.

</details>

---

<div align="center">
  <p>Terima kasih telah meninjau proyek ini!</p>
</div>
