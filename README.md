# MongoDB and No SQL Databases ( Database Server ) 

### Pengantar Database Server
Server database menyimpan, mengelola, dan mengambil data dalam format terstruktur. Fungsi utama meliputi penyimpanan, manajemen, pengolahan, kontrol, keamanan, indeks, cadangan, pemulihan, optimisasi, dan replikasi data.

### Perbandingan SQL dan NoSQL
- SQL: Bahasa pemrograman untuk database relasional.
- NoSQL: Jenis database mendukung model data beragam seperti dokumen, key-value, kolom, dan grafik.

### MongoDB Introduction
MongoDB menyimpan data dalam dokumen JSON/BSON. Keunggulan: skalabilitas, fleksibilitas skema, kinerja tinggi.

### Instalasi MongoDB
- [Download MongoDB Community Server](https://www.mongodb.com/try/download/community).
- Install MongoDB dan MongoDB Compass.
- Verifikasi instalasi melalui Windows Task Manager.

## Membaca, Memperbarui, dan Menghapus Data di MongoDB

### Membaca Data dari MongoDB

1. Buat file JavaScript baru (`readDocument.js`) untuk melakukan pembacaan data dari MongoDB.
2. Manfaatkan kode yang telah disediakan untuk membaca data dengan kriteria tertentu dari koleksi MongoDB.

### Memperbarui Data di MongoDB

1. Buat file JavaScript baru (`updateDocument.js`) untuk melakukan pembaruan data di MongoDB.
2. Gunakan kode yang telah disediakan untuk merubah data berdasarkan kriteria tertentu di dalam koleksi MongoDB.

### Menghapus Data dari MongoDB

1. Buat file JavaScript baru (`deleteDocument.js`) untuk menghapus data dari MongoDB.
2. Terapkan kode yang diberikan untuk menghapus data berdasarkan kriteria tertentu dari koleksi MongoDB.

## Penjelasan Singkat

### Instalasi MongoDB:

1. Lakukan pengunduhan dan pemasangan MongoDB Community Server.
2. Ikuti langkah-langkah pada instalator hingga selesai.

### Koneksi dan Penyisipan Data:

1. Bangun koneksi ke MongoDB menggunakan Node.js dan pustaka mongodb.
2. Lakukan penyisipan data ke dalam koleksi MongoDB dengan menggunakan perintah `insertOne` dan `insertMany`.

### Membaca Data dari MongoDB:

1. Ambil data dari MongoDB melalui perintah `findOne` dan `find`.
2. Terapkan kriteria pencarian untuk membaca data tertentu dari dalam koleksi.

### Memperbarui Data di MongoDB:

1. Lakukan pembaruan data di MongoDB menggunakan perintah `updateOne` dan `updateMany`.
2. Tentukan data yang akan diubah dengan menggunakan kriteria tertentu.

### Menghapus Data dari MongoDB:

1. Hapus data dari MongoDB melalui perintah `deleteOne` dan `deleteMany`.
2. Pilih kriteria penghapusan data dari koleksi.
