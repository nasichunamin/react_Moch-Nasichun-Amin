# Resume Materi GraphQL

## GraphQL
GraphQL merupakan suatu query language untuk API kita, dimana kita bisa mendefine data yang akan kita kirim ke client, dan kita bisa meminimize jumlah data. Didalam graphQL ada beberapa fitur yaitu
* Query        -> untuk mendapatkan data (get data)
* Mutation     -> untuk manipulasi data (insert, update, delete data)
* Subscription -> untuk mendapatkan data paling update

## Query
Query digunakan untuk mendapatkan data (get data). ada beberapa macam query yaitu query basic, query multiple related data source/ collection, query multiple unrelated data source/ collection, query fragments.

## Mutation
Mutasi pada dasarnya adalah fungsi untuk menambah data, mengubah data dan menghapus data. Kita perlu mendefinisikan operasi apa yang ingin kita lakukan (berdasarkan operasi yang tersedia di server graphql Anda) dan kemudian menentukan data apa yang GraphQL perlu kembalikan.

# Uraian Praktikum
- Membuat database di hasura
- Membuat data table anggota yang berisikan id(primary key, auto increment) dan nama
- Membuat data table anggota yang berisikan id(primary key, auto increment), id_anggota, pelajaran, nilai, status(boolean)
- melakukan query untuk memanggil hanya siswa yang memiliki status true
- melakukan insert kepada data angga dengan menggunakan mutation
- melakukan update data yang memiliki nilai false menjadi true menggunakan mutation