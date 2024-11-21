Nama: Rio Ade Zaputra
NIM/Kelas: 2205101076/5D
SEMANTIC-HTML
Latihan Praktikum Semantic HTML.

Semantic HTML Project
# Sematik-HTML
Berikut adalah parafrase dari teks analisis yang Anda berikan, dengan struktur yang lebih sederhana dan ringkas:

---

Analisis Proyek Semantic HTML

Struktur HTML
1. Penerapan Struktur:
   - Dokumen telah mengikuti standar HTML5 dengan penggunaan elemen utama seperti `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>`.
   - Elemen semantik seperti `<header>`, `<nav>`, `<section>`, dan `<footer>` digunakan dengan baik untuk meningkatkan aksesibilitas dan keterbacaan.

2. Kekurangan:
   - `<section>`: Hanya berisi teks tanpa elemen tambahan. Disarankan menambahkan elemen seperti paragraf (`<p>`) atau heading (`<h1>` hingga `<h6>`) agar lebih informatif.
   - **Teks Hak Cipta di `<footer>`: Sebaiknya gunakan entitas HTML `&copy;` untuk menampilkan simbol hak cipta sesuai standar.

---

Analisis CSS**
1. Penerapan yang Sudah Tepat:
   - `display: grid`: Telah diterapkan pada elemen `body` untuk mengatur tata letak berbasis grid, dengan `grid-template-areas` yang membagi area seperti header, nav, section, dan footer secara rapi.
   - `grid-template-rows` dan `grid-template-columns`**: Digunakan untuk menentukan tinggi dan lebar baris serta kolom dalam grid.

2. Kekurangan:
   - Responsivitas: Tata letak grid belum optimal pada layar kecil. Disarankan menambahkan media queries untuk memastikan desain tetap adaptif di perangkat mobile.
   - **Warna Latar Belakang Section: Warna #ababab memiliki kontras rendah dengan teks. Perlu ditinjau untuk meningkatkan keterbacaan.
   - **Ukuran Font di Footer: `font-size: small;` berisiko menghasilkan teks yang terlalu kecil. Sebaiknya pastikan ukuran tetap terbaca di layar kecil.
   - Grid di `body`: Penggunaan `height: 100vh` pada elemen `body` dapat menyebabkan masalah scroll di layar kecil. Disarankan menggantinya dengan `min-height: 100vh` agar lebih fleksibel.

---

Kesimpulan
1. Struktur dan Elemen: Sudah cukup baik, tetapi `<section>` perlu ditingkatkan informasinya.
2. Responsivitas:** Perlu ditingkatkan untuk layar kecil.
3. Aksesibilitas dan Keterbacaan: Perlu perbaikan pada warna latar belakang dan ukuran teks.

---

Ringkasan ini dapat dijadikan panduan untuk meningkatkan kualitas struktur HTML dan styling CSS pada proyek Anda. 😊
