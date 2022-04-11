# Resume Relational Database

## Introduction Database
Database adalah sekumpulan data yang terorganisir sehingga mudah dalam pengelolaannya. melalui pengelolaan tersebut dapat memperoleh kemudahan dalam mencari informasi, menyimpan informasi dan membuang informasi.

## Database Relationship
Database Relationship adalah sebuah hubungan entity dalam database. ada beberapa jenis relationship yaitu :
* one to one relationship
* one to many relathionship
* many to many relathionship
Relational Database Management Systems software yang menggunakan Relational Database Model sebagai dasarnya. contohnya mySQL.

## Jenis Perintah SQL
Tipe Data dalam sql ada beberapa yaitu number, huruf, dan date.
Jenis Perintah SQL :
* DDL
  Data Definition Language biasanya berisi query query untuk membuat database, membuat table, menghapus table, dll.
* DML
  Data Manipulation Language adalah perintah yang digunakan untuk memanipulasi data dalam tabel dari suatu database, seperti insert, select, update, delete. Di dalam DML ada DML Statement seprti LIKE/BETWEEN, AND/OR, ORDER BY, LIMIT.
* DCL
  Data Control Language adalah perintah yang digunakan untuk pengontrolan data dan server di database


# Uraian Praktikum
Nomor 1 :
- Pada gambar 1 saya membuat id_anggota pada table keterangan foreign key(FK) atau relationship dengan id.anggota sehingga id_anggota pada table keterangan akan terhubung dengan nama pada table anggota.
- pada gambar 2 contoh ketika saya menambahkan data pelajaran, nilai, dan status pada table keterangan. masing masing data yang saya masukkan memiliki id_anggota masing - masing yang nantinya akan masuk kedalam nama anggota sesuai id_anggota yang dimasukkan
- Pada gambar 3 kita mempunyai data table yang berisi 3 anggota yang memiliki id masing - masing
- Pada gambar 4, 4.1, 4.2 contoh inputan data pada table keterangan tadi akan masuk kedalam tabel data masing masing anggota, jadi jika kita tadi menginputkan id_anggota 1 maka data keterangan tersebut akan masuk kedalam database Budi yang dimana id budi tersebut bernilai 1. begitupun dengan inputan yang lainnya, jika kita memasukkan id_anggota 2 data akan masuk ke table anggota bernama sita karena memiliki id 2, dan begitupun seterusnya

Kesimpulan : dengan penjelasan diatas maka hal yang telah dilakukan merepresentasikan relasi database one to one

Nomor 2 :
untuk relasi database one to many sudah direpresentasikan pada setiap data table anggota yang memiliki banyak data mata pelajaran yang ada dalam table keterangan, untuk contohnya seperti pada gambar 4, 4.1, 4.2, 