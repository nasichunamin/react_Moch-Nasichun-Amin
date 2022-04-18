# Resume GraphQL Subscription 

## Subscription
Subcription adalah fitur GraphQL yang memungkinkan server mengirim data ke kliennya saat peristiwa tertentu terjadi. Subcription biasanya diimplementasikan dengan WebSockets. Dalam pengaturan itu, server mempertahankan koneksi yang stabil ke klien. Ketika data diubah maka klien akan mendapatkan data yang diperbarui secara langsung secara **real-time**.

## Subscription React
Untuk menggunakan subscription di react harus menginstall module graphql ws terlebih dahulu. lalu setting apollo client seperti pada dokumentasi yang ada [disini](https://www.apollographql.com/docs/react/data/subscriptions).

# Uraian Praktikum Subscription
Menambahkan atau menggunakan subscription untuk project kita sebelumnya. jadi data yang akan tampil akan secara **real-time** terupdate.