# Praktikum-2

## DDL (Data Definition Language) &  DML (Data Manipulation Language) 

- DDL dan DML adalah dua jenis perintah atau instruksi yang digunakan dalam SQL (Structured Query Language) untuk mengakses dan memanipulasi database.

- DDL (Data Definition Language) digunakan untuk membuat, mengubah, dan menghapus objek dalam database seperti tabel, indeks, dan constraint. Contoh perintah DDL antara lain CREATE, ALTER, dan DROP.

- Sementara itu, DML (Data Manipulation Language) digunakan untuk memanipulasi data dalam objek database seperti tabel. Contoh perintah DML antara lain SELECT, INSERT, UPDATE, dan DELETE.

- Dalam ringkasan, DDL dan DML keduanya digunakan dalam SQL tetapi memiliki fungsi yang berbeda. DDL digunakan untuk mengelola objek dalam database, sementara DML digunakan untuk mengelola data dalam objek database.

![img.1](Screenshot/Tampilan%20ERD.png)

Transform ER-D ke dalam Mapping Table

Data Model Mapping
- Mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, - jalan, kota, kodepos, no_hp, kd_ds)
- Dosen (kd_ds, nama)
- Matakuliah (kd_mk, nama, sks)
- JadwalMengajar (kd_ds, kd_mk, hari, jam, ruang)
- KRSMahasiswa (nim, kd_mk, kd_ds, semester, nilai)

# Evaluasi & Pertanyaan

1. Apa bedanya penggunaan BETWEEN dan penggunaan operator >= dan <=?

=> Perbedaan utama antara penggunaan BETWEEN dan operator >= dan <= adalah bahwa BETWEEN menyertakan kedua nilai batas dalam rentang, sedangkan operator >= dan <= bisa memeriksa nilai yang sama dengan nilai batas tetapi tidak menyertakan nilai batas itu sendiri.

Dalam kebanyakan kasus, keduanya dapat digunakan secara bergantian dan akan menghasilkan hasil yang sama. Namun, penggunaan BETWEEN dapat membuat sintaks SQL lebih mudah dibaca dan mudah dipahami karena hanya memerlukan satu kata kunci untuk memeriksa rentang, sementara operator >= dan <= memerlukan dua operator yang harus digunakan secara bersamaan.


2. Berikan kesimpulan anda!

=> 
- DDL digunakan untuk membuat, mengubah, dan menghapus objek dalam database seperti tabel, indeks, dan constraint.
- DML digunakan untuk memanipulasi data dalam objek database seperti tabel.
- DDL dan DML keduanya digunakan dalam SQL tetapi memiliki fungsi yang berbeda.
- DDL digunakan untuk mengelola objek dalam database, sementara DML digunakan untuk mengelola data dalam objek database.
- DDL dan DML merupakan dua jenis perintah atau instruksi yang penting dalam SQL untuk mengakses dan memanipulasi database.