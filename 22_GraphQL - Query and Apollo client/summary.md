# Resume GraphQL - Query and Apollo Client

## Hasura & Heroku
Hasura adalah sebuah web layanan yang menyediakan graphql dan rest api. Dikelola penuh di cloud hasura atau dihosting sendiri.<br>

Heroku adalah platform cloud sebagai layanan yang mendukung beberapa bahasa pemrograman. Heroku juga menyediakan database postgres gratis.<br>

## Apollo Client
Apollo Client adalah perpustakaan manajemen status komprehensif untuk JavaScript yang memungkinkan kami mengelola data lokal dan jarak jauh dengan GraphQL. Biasanya Digunakan untuk mengambil, menyimpan, dan memodifikasi data aplikasi, sambil memperbarui UI secara otomatis. Pustaka inti @apollo/client menyediakan integrasi bawaan dengan React. Kami menggunakan klien Apollo untuk melakukan operasi GraphQL (kueri, mutasi, dan berlangganan) di dalam aplikasi React atau Next JS kami. Klien Apollo bekerja dengan baik dengan server GraphQL (Hasura, Apollo Server, dll)

## Query
Untuk menampilkan data bisa menggunakan Query dengan apollo client. untuk melakukan hal tersebut dalam react perlu menginstall library @apollo/client, lalu bisa menggunakan useQuery untuk menampilkan data dari database yang ada pada hasura.

# Uraian Praktikum GraphQL - Query and Apollo Client
Menghubungkan project react dengan GraphQL, lalu melakukan query pada database todolist. sehinga ketika aplikasi pertama kali dibuka, aplikasi langsung melakukan fetch data dan menampilkan data pada layar. setelah itu membuat fitur query berdasarkan inputan dari user. sehingga dapat menampilakn data sesuai dengan user id