<img width="1347" height="757" alt="image" src="https://github.com/user-attachments/assets/2b42e213-a578-4b19-be44-d2da721c3863" />Lab8Web – PHP dan MySQL (CRUD Data Barang)

Nama: Aris Yulianto
NIM: 312510491
Kelas: I251D

Aplikasi CRUD sederhana untuk mengelola data barang menggunakan PHP dan MySQL.

1. Menjalankan Server

Start Apache dan MySQL di XAMPP Control Panel.

<img width="675" height="434" alt="image" src="https://github.com/user-attachments/assets/abb3563b-887f-49cb-842e-53c0d70aad70" />


2. Membuat Database dan Tabel

Buka http://localhost/phpmyadmin/, lalu import file database.sql. Script ini membuat database latihan1, tabel data_barang, dan 3 data awal.

<img width="1347" height="757" alt="image" src="https://github.com/user-attachments/assets/97f73f95-b93d-46ef-a025-1e5b1d370b35" />

3. Koneksi Database (koneksi.php)

Menghubungkan PHP ke database latihan1 dengan mysqli_connect().

<img width="734" height="451" alt="image" src="https://github.com/user-attachments/assets/98b3b1ed-65cc-465c-a6d5-596cb1649265" />


4. Menampilkan Data – Read (index.php)

Mengambil semua data dengan SELECT * FROM data_barang dan menampilkannya dalam tabel.

<img width="1352" height="744" alt="image" src="https://github.com/user-attachments/assets/c3140cf2-1d3a-4dda-999f-a776cdd7c13d" />


5. Menambah Data – Create (tambah.php)

Form untuk input barang baru beserta upload gambar. Data disimpan dengan INSERT.

<img width="1348" height="756" alt="image" src="https://github.com/user-attachments/assets/0fbd3c58-43d0-42ce-8718-2f38e8ce718f" />


6. Mengubah Data – Update (ubah.php)

Menampilkan data lama di form, lalu menyimpan perubahan dengan UPDATE.

<img width="1365" height="768" alt="image" src="https://github.com/user-attachments/assets/1d88ccec-3d79-42b2-929e-b82e27314921" />


7. Menghapus Data – Delete (hapus.php)

Menghapus data berdasarkan id dengan DELETE.

<img width="1334" height="766" alt="image" src="https://github.com/user-attachments/assets/65e07d38-c745-4376-8408-253b0bbf6a3f" />


Cara Menjalankan
Salin folder project ke htdocs/lab8_php_database.
Import database.sql lewat phpMyAdmin.
Buka http://localhost/lab8_php_database/.
