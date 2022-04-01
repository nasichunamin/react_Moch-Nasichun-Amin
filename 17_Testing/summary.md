# Resume React Testing

## Basic Testing
Testing adalah proses memverifikasi bahwa test assertions kita benar dan bahwa kode kita tetap benar sepanjang masa aplikasi. Test assertion ini adalah ekspresi boolean yang mengembalikan nilai true kecuali ada bug di kode kita.
Rekomendasi Tools Testing: 
1. Jest<br>
   Test runner pada JavaScript yang memungkinkan Anda mengakses DOM melalui jsdom. Sementara jsdom hanyalah perkiraan cara kerja browser, seringkali cukup baik mengetes komponen pada React. Jest memberikan kecepatan iterasi yang bagus dikombinasikan dengan fitur-fitur yang powerful seperti mocking modules dan timers sehingga Anda dapat memiliki kontrol lebih pada kode yang dijalankan.
2. React Testing Library <br>
   Merupakan seperangkat helpers yang memungkinkan kita mengetes komponen pada React tanpa bergantung pada detail implementasinya. Pendekatan ini membuat refactoring menjadi mudah dan juga mendorong kita untuk menerapkan best practices untuk aksesibilitas. Mungkin tidak memberikan cara untuk me-render secara “dangkal” pada sebuah komponen tanpa anak, test runner seperti Jest yang memungkinkan kita melakukan mocking.

## Manfaat Testing
Walaupun menambahkan waktu dan code dalam membuat testing, testing memiliki manfaat sebagai berikut:
* Ketika aplikasi kita mempunyai coverage yang baik (mayoritas codebase tercover oleh test), Kita akan merasa percaya diri jika harus mengubah suatu bagian pada aplikasi kita. Saat kita mengubah bagian tersebut, dan ada bagian yang lain menjadi broken kita akan segera mengetahuinya.
* Mengurangi bug pada aplikasi. Walaupun testing tidak menjamin aplikasi kita bebas bug, tetapi kita bisa mencegah beberapa hal yang berpotensi menjadi bug.

## Kategori Testing
Secara umum, cara mengetes di React terbagi menjadi dua kategori:
* Rendering component trees di dalam environment tes yang sudah disederhanakan dan ditegaskan pada keluarannya. Kita akan fokus pada bagian ini.
* Menjalankan aplikasi lengkap di dalam environment peramban (browser) asli. Ini dikenal sebagai tes “end-to-end”.

# Uraian Tugas Praktikum
Membuat file testing untuk code code yang disediakan. Semakin banyak dan berkualitas skenario testing maka akan semakin bagus.
