# Praktikum2
praktikum 1
Data Model Mapping

#### 1.Mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, jalan, kota, kodepos, no_hp, kd_ds)
#### 2.Dosen (kd_ds, nama)
#### 3.Matakuliah (kd_mk, nama, sks)
#### 4.JadwalMengajar (kd_ds, kd_mk, hari, jam, ruang)
#### 5.KRSMahasiswa (nim, kd_mk, kd_ds, semester, nilai)
Buat DDL Script berdasarkan skema ERD tersebut diatas. Jalankan script DDL tersebut pada DBMS MySQL

1.Script Tabel mahasiswa

![image](https://user-images.githubusercontent.com/115569493/232498337-4e04c6da-6b1f-4fac-84f4-2a3fcf821871.png)

output

![image](https://user-images.githubusercontent.com/115569493/232498448-ce07fc72-02fd-40b7-b308-172f4e06f8c3.png)

2.Script Tabel dosen

![image](https://user-images.githubusercontent.com/115569493/232498800-2ceba03b-ad96-481c-891a-5204f279cd93.png)

output

![image](https://user-images.githubusercontent.com/115569493/232498912-cc5bc4d6-1284-4029-8837-68a51d3d0531.png)

3.Script Tabel matakuliah

![image](https://user-images.githubusercontent.com/115569493/232499156-8d1c1a78-e5a8-44af-aa36-88c91ce5fdb9.png)

OUTPUT

![image](https://user-images.githubusercontent.com/115569493/232915475-e594563d-1907-42ab-9cbc-1a0a7301dd16.png)

4.Script Tabel JadwalMengajar

![image](https://user-images.githubusercontent.com/115569493/232915615-576b6a84-b7cb-468f-a8ec-bc61957311ed.png)

output

![image](https://user-images.githubusercontent.com/115569493/232915690-d1192fca-ffd7-402d-bec5-e5c21256779f.png)

5.Script Tabel KRSmahasiswa

![image](https://user-images.githubusercontent.com/115569493/232915868-feb6f26a-2daa-4925-8336-90c7bfb0206b.png)

output

![image](https://user-images.githubusercontent.com/115569493/232915902-fb2ecec4-f5e8-45b6-bf69-2ec7291cb499.png)
DDL script

![image](https://user-images.githubusercontent.com/115569493/232916006-60724f4a-9287-4c0f-9d75-839687639d34.png)

# Tugas Praktikum 2

1. Isi data pada table tersebut sebanyak minimal 5 record data.
2. Tampilkan semua isi/record tabel! 
3. Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 1979-08-31! 
4. Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan nama Ari saja! 
5. Hapus Mahasiswa yang bernama Dina! 
6. Tampilkan record atau data yang tanggal kelahirannya lebih dari atau sama dengan 1996-1-2! 
7. Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin perempuan! 
8. Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita!
9. Tampilkan data nama dan alamat mahasiswa saja dari tabel tersebut
10. Tampilkan data mahasiswa terurut berdasarkan nama


1.Isi data pada table tersebut sebanyak minimal 5 record data. 

![image](https://user-images.githubusercontent.com/115569493/232916329-2e40a7c8-324c-408d-9e4e-8f96104a724a.png)


2.Tampilkan semua isi/record tabel! 

![image](https://user-images.githubusercontent.com/115569493/232916417-fb604550-a792-4fb0-8515-d306d96a3633.png)


3.Ubah data tanggal lahir mahasiswa yang bernama Ari menjadi: 1979-08-31! 

![image](https://user-images.githubusercontent.com/115569493/232916488-1e727bd3-f0f1-4164-9fc6-d673d684305b.png)


4.Tampilkan satu baris / record data yang telah diubah tadi yaitu record dengan nama Ari saja! 

![image](https://user-images.githubusercontent.com/115569493/232916521-39e45891-774c-4325-9a09-180f0304a5e6.png)


5.Hapus Mahasiswa yang bernama Dina! 

![image](https://user-images.githubusercontent.com/115569493/232916584-09d1f062-7ea6-4691-9248-3321beab8ad4.png)


6.Tampilkan record atau data yang tanggal kelahirannya lebih dari atau sama dengan 1996-1-2

![image](https://user-images.githubusercontent.com/115569493/232916674-e7252968-5639-4bb5-af0d-15ce4212f939.png)


7.Tampilkan semua Mahasiswa yang berasal dari Bekasi dan berjenis kelamin perempuan

![image](https://user-images.githubusercontent.com/115569493/232916720-b0f8afca-28d3-4255-866b-b000baedcd0e.png)


8.Tampilkan semua Mahasiswa yang berasal dari Bekasi dengan kelamin laki-laki atau Mahasiswa yang berumur lebih dari 22 tahun dengan kelamin wanita

![image](https://user-images.githubusercontent.com/115569493/232916790-9e559ff1-fb20-4d43-be88-2d819d7d6b63.png)


9.Tampilkan data nama dan alamat mahasiswa saja dari tabel tersebut 

![image](https://user-images.githubusercontent.com/115569493/232916943-fa471dc6-bb7b-4f66-993a-5389682b404e.png)


10.Tampilkan data mahasiswa terurut berdasarkan nama 

![image](https://user-images.githubusercontent.com/115569493/232916972-db3ddec5-3169-4f8c-8206-6f2cc1dd459c.png)


### Evaluasi dan Pertanyaan

Apa bedanya penggunaan BETWEEN dan penggunaan operator >= dan <= ? (misal: tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11') (misal: tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11')
Operator BETWEEN digunakan untuk memeriksa apakah sebuah nilai berada di antara dua nilai yang diberikan, termasuk kedua nilai tersebut. Contoh penggunaannya adalah tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11', yang artinya mengambil data dengan tanggal lahir di antara 10 Oktober 1990 dan 11 Oktober 1992, termasuk kedua tanggal tersebut.
Sedangkan operator >= dan <= digunakan untuk membandingkan nilai dan mengambil data dengan nilai yang lebih besar atau lebih kecil dari suatu nilai tertentu. Contoh penggunaannya adalah tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11', yang artinya mengambil data dengan tanggal lahir yang lebih besar atau sama dengan 10 Oktober 1990 dan lebih kecil atau sama dengan 11 Oktober 1992.
### Berikan kesimpulan anda!
Data Manipulation Language (DML) adalah bahasa pemrograman yang digunakan untuk mengakses, memanipulasi dan mengelola data dalam database. DML memungkinkan pengguna untuk melakukan operasi seperti menambahkan data baru, memperbarui data yang ada, menghapus data, dan mengambil data untuk mendapatkan data yang dibutuhkan.

#### Di DML, pengguna dapat mengakses data menggunakan perintah SQL (Structured Query Language). SQL adalah bahas




