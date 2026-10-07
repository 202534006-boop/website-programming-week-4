# Dokumentasi Pengujian Tugas 4

## 1. Pengujian Layar Lebar

Halaman diuji pada ukuran layar lebar. Navigasi, bagian main dan aside, serta card dapat tampil dengan baik menggunakan Flexbox.

## 2. Pengujian Viewport 320px

Halaman diuji pada viewport sekitar 320 CSS px. Main dan aside menyesuaikan menjadi satu kolom dan navigasi dapat berpindah ke baris berikutnya. Tidak terdapat horizontal scroll pada konten utama.

## 3. Pengujian Flexbox

Flexbox diperiksa melalui Chrome DevTools. Container yang menggunakan Flexbox dapat terlihat dan item di dalamnya mengikuti pengaturan `flex-wrap`, `gap`, dan `flex-basis`.

## 4. Pengujian Keyboard

Navigasi dan elemen form diuji menggunakan keyboard. Urutan fokus mengikuti urutan elemen pada HTML dan indikator fokus terlihat dengan jelas.

## 5. Pengujian Zoom

Halaman diuji pada zoom 200%. Badge tetap berada pada posisi yang sesuai dan tidak menutupi isi card.

## 6. Pengujian Media

Gambar diuji pada ukuran layar yang berbeda. Gambar tidak melebihi lebar container karena menggunakan `max-width: 100%`.

## 7. Pengujian HTML

Halaman diperiksa menggunakan Nu HTML Checker dan tidak ditemukan error atau warning.

## 8. Pengujian Console

Chrome DevTools Console diperiksa dan tidak terdapat error JavaScript.

## 9. Masalah dan Perbaikan

Salah satu hal yang diperhatikan adalah kemungkinan terjadinya overflow pada item Flexbox ketika ruang layar menjadi sempit. Untuk membantu mencegah masalah tersebut digunakan `min-width: 0` pada item card.

## Kesimpulan

Layout Tugas 4 menggunakan normal flow sebagai dasar dan Flexbox untuk navigasi, layout main dan aside, serta card. Layout dapat menyesuaikan ukuran layar tanpa mengubah urutan visual dari struktur HTML.
