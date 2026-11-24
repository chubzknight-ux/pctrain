# Aturan update
Setiap update yang mengubah tampilan/alur WAJIB:
1. Naikkan `APP_VERSION` dan tambah entri paling atas di `CHANGELOG` (`public/index.html`) → popup "Apa yang baru" muncul sekali untuk pengguna lama.
2. Perbarui `LEGEND` bila ada warna/ikon/elemen baru.
3. Naikkan `CACHE` di `public/sw.js`.
