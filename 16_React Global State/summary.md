# Resume Global State Management and Data Fetching

## Global State Introduction
Global State management adalah data yang dibagikan ke semua komponen dalam react. untuk mengirim data data tersebut kita bisa menggunakan redux store.<br>

Redux adalah library untuk manajemen state global. Redux menggunakan struktur "One-way data flow". Lalu, kapan saat yang tepat untuk menggunakan Redux?

* Banyak state yang perlu ditaruh di banyak tempat
* State pada app sering berubah
* Logic untuk mengubah state kompleks
* Ukuran codebase yang sedang-besar, dan dikerjakan oleh banyak orang
* Perlu untuk mengetahui bagaimana state diupdate seiring waktu.
<br>

Redux Library and Tools :
* React-Redux
* Redux Toolkit
* Redux DevTools Extension
-------------
<br>

* Action
  Digunakan untuk memberikan informsi dari aplikasi ke store
* Reducer
  Pure Javascript function yang mengambil state aplikasi saat ini dan object action lalu mengembalikan state aplikasi terbaru
* Store
  Objek sentral yang menyimpan state pada aplikasi

## Redux Thunk
Thunk Middleware untuk redux yang memungkinkan kita untuk membuat action creator yang mengembalikan function bukan action. Mengapa perlu redux thunk? kita perlu redux thunk untuk menghandle side effect logic seperti logic synchronous kompleks yang perlu mengakses store dan juga logic async seperti request data.

## Data Fetching
Data fetching adalah mengambil data dari server yang dimana kita request data dari server dan nantinya akan memberi respon ke app kita sesuai dengan data yang kita request. Cara cara untuk fetching data di react adalah fetch API, Axios, React Query Library.
