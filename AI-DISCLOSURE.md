# AI-DISCLOSURE

## 1. Penggunaan AI

Saya menggunakan AI sebagai alat bantu dalam mengerjakan Tugas 4 Layout Fleksibel. AI digunakan untuk membantu memahami konsep CSS Flexbox, responsive layout, overflow, alignment, dan pengujian halaman web.

AI tidak digunakan untuk menggantikan pemahaman dan pengerjaan secara keseluruhan. Saya tetap menyesuaikan kode dengan proyek SASHANO, melakukan pengujian, dan melakukan perubahan secara mandiri.

## 2. Prompt yang Digunakan

Beberapa prompt yang saya gunakan selama pengerjaan tugas adalah:

1. "Bagaimana cara membuat layout main dan aside menggunakan Flexbox?"
2. "Bagaimana cara membuat menu navigasi dapat turun ke baris berikutnya ketika layar dipersempit?"
3. "Bagaimana cara membuat main dan aside menjadi satu kolom pada layar sempit?"
4. "Bagaimana cara membuat minimal tiga card fleksibel menggunakan Flexbox?"
5. "Bagaimana cara membuat badge menggunakan position relative dan position absolute?"
6. "Bagaimana cara memastikan gambar tidak melebihi ukuran container?"
7. "Bagaimana cara memperbaiki masalah overflow atau alignment pada layout Flexbox?"
8. "Bagaimana cara melakukan pengujian keyboard menggunakan tombol Tab?"
9. "Bagaimana cara mengecek layout Flexbox menggunakan Developer Tools?"
10. "Bagaimana cara membuat AI-DISCLOSURE untuk tugas website?"

## 3. Saran AI yang Digunakan

Saran dari AI yang saya gunakan dalam tugas ini antara lain:

- Menggunakan `display: flex` untuk membuat layout fleksibel.
- Menggunakan `flex-wrap: wrap` pada navigasi dan daftar card.
- Menggunakan `gap` untuk memberikan jarak antar elemen.
- Menggunakan `flex` dan `flex-basis` agar ukuran elemen dapat menyesuaikan ruang yang tersedia.
- Menggunakan `min-width: 0` pada elemen Flexbox untuk membantu mencegah overflow.
- Menggunakan media query untuk mengubah layout `main` dan `aside` menjadi satu kolom pada layar sempit.
- Menggunakan `position: relative` pada card sebagai acuan posisi badge.
- Menggunakan `position: absolute` pada badge.
- Menggunakan `max-width: 100%` dan `height: auto` agar gambar tidak keluar dari container.
- Menggunakan `overflow-wrap: anywhere` agar teks yang terlalu panjang dapat berpindah ke baris berikutnya.
- Menggunakan `:hover`, `:active`, dan `:focus-visible` untuk memberikan interaksi dan indikator fokus.

## 4. Pengujian

Setelah menerapkan saran tersebut, saya melakukan pengujian pada halaman website.

Pengujian yang dilakukan meliputi:

### a. Pengujian layar lebar

Saya memeriksa apakah `main` dan `aside` dapat tampil berdampingan pada layar yang cukup lebar.

### b. Pengujian layar sempit

Saya mengubah ukuran viewport menjadi sekitar 320 CSS px untuk memastikan:

- Navigasi dapat turun ke baris berikutnya.
- `main` dan `aside` menjadi satu kolom.
- Card dapat menyesuaikan ukuran layar.
- Tidak terdapat scroll horizontal.

### c. Pengujian zoom

Saya melakukan pengujian pada zoom 200% dan 400% untuk memastikan isi halaman tetap dapat dibaca dan tidak menyebabkan masalah layout.

### d. Pengujian keyboard

Saya menggunakan tombol `Tab` untuk berpindah dari satu elemen interaktif ke elemen berikutnya.

Saya memeriksa apakah:

- Urutan fokus mengikuti urutan isi halaman.
- Semua link, input, select, textarea, dan button dapat difokuskan.
- Indikator fokus terlihat dengan jelas.

### e. Pengujian Flexbox

Saya menggunakan Developer Tools untuk melihat elemen Flexbox dan memastikan container seperti `.nav-list`, `.page-layout`, dan `.card-list` menggunakan `display: flex`.

### f. Pengujian overflow

Saya memeriksa halaman pada layar sempit untuk memastikan tidak terdapat scroll horizontal.

Jika terdapat isi yang terlalu panjang, `min-width: 0` dan `overflow-wrap: anywhere` digunakan agar isi dapat menyesuaikan container.

### g. Pengujian file

Saya memeriksa apakah file HTML, CSS, dan gambar dapat dimuat dengan baik dan tidak menghasilkan error pada Console.

## 5. Perubahan Mandiri

Setelah mendapatkan saran dari AI, saya melakukan perubahan sendiri sesuai dengan kebutuhan website SASHANO.

Perubahan yang saya lakukan antara lain:

- Menyesuaikan isi halaman dengan kegiatan SASHANO.
- Menyesuaikan judul, navigasi, card, dan informasi peserta.
- Menyesuaikan ukuran dan tampilan gambar SASHANO.
- Menyesuaikan warna, jarak, ukuran teks, dan tampilan card.
- Menentukan sendiri ukuran dan posisi badge.
- Menyesuaikan breakpoint media query untuk layar sempit.
- Menambahkan dan menyesuaikan `min-width: 0` untuk membantu mengatasi overflow.
- Menambahkan `overflow-wrap: anywhere` untuk teks yang panjang.
- Menguji perubahan pada browser dan memperbaiki bagian yang belum sesuai.
- Memastikan urutan HTML tetap sesuai dengan urutan visual dan urutan keyboard