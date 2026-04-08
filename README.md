# Penjelasan Kode 

## 1. Bagian Head (Metadata & Library)
- **`<meta charset="UTF-8">`**: Menentukan pengkodean karakter universal agar teks tampil dengan benar.
- **`<meta name="viewport" ...>`**: Kunci utama agar website **Responsive**. Kode ini memastikan ukuran web menyesuaikan layar HP atau Laptop.
- **Bootstrap CDN**: Mengambil file CSS Bootstrap dari internet agar kita bisa memakai class seperti `container`, `row`, dan `btn` tanpa menulis CSS dari nol.
- **Internal Style**: 
  - `section`: Memberikan jarak (*padding*) atas dan bawah sebesar `5rem` agar konten antar bagian tidak menempel.
  - `.jumbotron`: Mengatur warna latar abu-abu terang, jarak dalam (*padding*), dan sudut yang melengkung (*border-radius*).

## 2. Bagian Navbar (Navigasi)
- **`navbar-expand-lg`**: Menu akan melebar di layar besar dan menjadi tombol "hamburger" di layar HP.
- **`fixed-top`**: Mengunci posisi navbar agar tetap di atas meskipun halaman di-scroll ke bawah.
- **`shadow-sm`**: Memberikan efek bayangan tipis di bawah navbar agar terlihat lebih modern.

## 3. Hero Section (Jumbotron)
- **`id="home"`**: Sebagai penanda (anchor) agar saat menu "Home" di klik, halaman otomatis bergeser ke sini.
- **`rounded-circle` & `img-thumbnail`**: Class Bootstrap untuk membuat foto profil berbentuk bulat dan memiliki bingkai putih tipis.
- **`display-4`**: Membuat ukuran font judul (Halo, Saya Ahmad Dani) menjadi sangat besar dan mencolok.
- **`alert-info`**: Menampilkan kotak informasi berwarna biru muda untuk menonjolkan pesan status belajar.

## 4. About Section (Tentang Saya)
- **`bg-light`**: Memberikan latar belakang abu-abu sangat muda untuk membedakan bagian ini dengan bagian lainnya.
- **`row` & `col-md-4`**: Implementasi **Flexbox/Grid**. Konten dibagi menjadi kolom-kolom. Di layar laptop (md), teks akan berjajar ke samping, sedangkan di HP akan bertumpuk ke bawah.
- **`justify-content-center`**: Memastikan konten teks berada tepat di tengah halaman.

## 5. Projects Section (Daftar Karya)
- **`card`**: Komponen Bootstrap untuk membungkus konten proyek dalam kotak yang rapi.
- **`shadow-sm`**: Memberikan efek kedalaman pada kotak proyek agar terlihat "timbul".
- **`btn-primary`, `btn-warning`, `btn-danger`**: Memberikan warna tombol yang berbeda (biru, kuning, merah) sebagai indikator status proyek (Selesai, Proses, atau Pending).

## 6. Footer (Bagian Bawah)
- **`bg-primary`**: Menggunakan warna biru utama yang konsisten dengan Navbar.
- **`text-white`**: Memastikan teks hak cipta berwarna putih agar mudah dibaca di atas latar biru.

---
*Dibuat untuk memenuhi Tugas 2 Pemrograman Web - 2026*