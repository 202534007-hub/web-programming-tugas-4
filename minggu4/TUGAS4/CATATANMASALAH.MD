### Catatan Masalah Overflow

Masalah yang ditemukan adalah teks atau isi card yang terlalu panjang dapat menyebabkan elemen melebar dan berpotensi menimbulkan scroll horizontal pada layar yang sempit.

Untuk memperbaikinya, saya menambahkan `min-width: 0` pada elemen Flexbox seperti `main`, `aside`, dan card. Selain itu, saya menggunakan `overflow-wrap: anywhere` agar teks yang panjang dapat berpindah ke baris berikutnya. Dengan perbaikan tersebut, isi halaman dapat menyesuaikan ukuran layar dan tidak menyebabkan overflow horizontal.