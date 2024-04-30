Penjelasan Kode HTML:

1. Deklarasi HTML (`<!DOCTYPE html>`): Mendefinisikan bahwa dokumen ini adalah dokumen HTML.

2. Elemen `<html>`: Menandai awal dan akhir dari dokumen HTML. Atribut `lang="en"` menunjukkan bahasa dokumen.

3. Elemen `<head>`: Bagian ini berisi metadata dan informasi lain yang terkait dengan dokumen HTML.
    - Metadata: Menggunakan elemen `<meta>` untuk mendefinisikan karakter set dokumen (`<meta charset="UTF-8">`) dan pengaturan tampilan layar (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`).
    - Judul Halaman: Ditentukan oleh elemen `<title>`, yang menampilkan judul halaman di tab browser.
    - 
4. Elemen `<body>`: Ini adalah bagian utama dari dokumen HTML yang berisi semua konten yang akan ditampilkan di halaman web.
    - Navbar (`<nav class="navbar">`)**: Menampilkan menu navigasi di bagian atas halaman. Terdiri dari logo dan daftar menu dengan kelas `.navbar-nav`. Setiap menu ditandai dengan elemen `<li>` dan `<a>`.
    - Konten Utama**: Bagian ini, dikelompokkan dalam elemen `<div class="container">`, berisi konten utama halaman, termasuk judul, daftar posting blog terbaru, tips kecantikan, dan ulasan produk. Setiap bagian konten diwakili oleh elemen `<div class="feature-box">` yang berisi judul, deskripsi, gambar, dan tautan.
    - Footer: Ditandai oleh elemen `<footer>`, bagian ini menampilkan informasi kontak, tautan menu, dan hak cipta. Informasi kontak ditampilkan dalam `<div>` terpisah, diikuti oleh tautan menu dan hak cipta.
