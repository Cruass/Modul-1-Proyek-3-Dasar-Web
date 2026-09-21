# Modul-1-Dasar-Web
# Praktikum Modul 1 - Muhammad Rayhan Maulana Farid / 251511054

## Ringkasan halaman

Pada praktikum Modul 1, saya mempelajari dasar-dasar HTML dan CSS untuk membuat halaman web sederhana berupa profil mahasiswa.

Saya belajar menggunakan struktur HTML semantik seperti `header`, `nav`, `main`, `section`, dan `footer`. Saya juga mempelajari penggunaan CSS eksternal untuk mengatur warna, ukuran tulisan, jarak, dan tampilan card pada halaman.

Selain itu, saya mencoba menggunakan Flexbox agar bagian Tentang Saya, Keterampilan, dan Kontak dapat tersusun secara horizontal serta menyesuaikan tampilan pada layar yang lebih kecil.

## 3 Keputusan Teknis

1. Menggunakan HTML semantik agar struktur halaman lebih teratur dan mudah dipahami.

2. Menggunakan file CSS eksternal agar kode HTML dan CSS terpisah sehingga lebih mudah diperbaiki dan dikembangkan.

3. Menggunakan Flexbox pada `.profile-container` untuk mengatur posisi beberapa card dan menggunakan media query agar tampilan dapat menyesuaikan ukuran layar.

## Satu kesalahan yang membantu proses belajar

Saya sempat menambahkan class `.profile-container` dan `.card` pada HTML, tetapi perubahan tampilan belum terlihat di browser.

Hal tersebut membuat saya belajar untuk memeriksa apakah file CSS sudah terhubung dengan benar, apakah file sudah disimpan, dan apakah browser masih menampilkan tampilan lama.

Dari kesalahan ini, saya memahami bahwa perubahan kode tidak selalu langsung terlihat jika file yang digunakan salah atau halaman belum diperbarui.

## Satu bagian yang masih perlu ditingkatkan

Saya masih perlu meningkatkan pemahaman tentang Flexbox dan responsive design.

Saya sudah memahami bahwa `display: flex` dapat menyusun elemen secara horizontal, tetapi masih perlu belajar lebih banyak tentang penggunaan `flex`, `gap`, `align-items`, dan `flex-direction`.

Saya juga perlu lebih memahami cara menentukan breakpoint yang sesuai agar tampilan web tetap rapi pada berbagai ukuran layar.

## Masalah, diagnosis, dan perbaikan

- Masalah yang saya temui adalah tampilan tiga bagian profil belum berubah menjadi card yang berjajar.
- Saya memeriksa kembali penggunaan class pada HTML dan CSS.
- Saya memastikan bahwa setiap section memiliki class `.card`.
- Saya memastikan bahwa ketiga section berada di dalam elemen dengan class `.profile-container`.
- Saya menambahkan `display: flex` pada `.profile-container`.
- Saya menggunakan `flex-direction: column` pada media query agar card tersusun ke bawah pada layar kecil.
- Saya juga memeriksa file `style.css`, menyimpan perubahan, dan melakukan refresh browser menggunakan `Ctrl + F5`.

## Hasil pengujian empat viewport

Saya melakukan pengujian pada beberapa ukuran layar untuk melihat perubahan tampilan halaman.

Pada layar desktop, bagian Tentang Saya, Keterampilan, dan Kontak dapat disusun secara horizontal. Pada layar yang lebih kecil, ketiga bagian tersebut disusun secara vertikal agar isi halaman lebih mudah dibaca.

Pengujian ini membantu saya memahami bahwa tampilan web perlu dibuat responsive, bukan hanya disesuaikan untuk satu ukuran layar.

## Hal yang saya pelajari

Dari praktikum ini, saya memahami bahwa HTML digunakan untuk membangun struktur dan isi halaman, sedangkan CSS digunakan untuk mengatur tampilan halaman.

Saya juga belajar bahwa penggunaan elemen semantik membuat struktur HTML lebih jelas. Penggunaan class membantu saya menerapkan style pada beberapa elemen dengan lebih mudah.

Selain itu, saya mulai memahami cara kerja Flexbox untuk mengatur layout dan media query untuk membuat halaman menyesuaikan ukuran layar.

## Log AI atau sumber bantuan

- Materi Praktikum Modul 1.
- Penjelasan dosen.
- Dokumentasi dasar HTML dan CSS.
- Bantuan AI yaitu Gemini AI.
