# Resume React Form

## Basic Form
Form merupakan salah satu hal krusial dalam pengembangan aplikasi website. Form dapat digunakan untuk menghandle inputan dari user. Form banyak kita jumpai saat login, mendaftarkan sesuatu, memberikan feedback, mengisi data dan masih banyak lainnya. Ada beberapa macam form yaitu :
* Elemen Input
* Elemen TextArea
* Elemen Select
* Radio Button
* Checkbox
* dsb

## Controlled Component and Uncontrolled Component
1. Controlled Component
   Kita dapat menggabungkan cara menyimpan dan memperbarui state di HTML dan React dengan menggunakan state pada React. Kemudian Komponen React yang me-render sebuah form juga mengontrol apa yang terjadi dalam form tersebut pada masukan pengguna selanjutnya.
    Sebuah elemen masukan form yang nilainya dikontrol oleh React melalui cara seperti ini disebut sebagai ”controlled component“.
2. Uncontrolled Component
   Uncontrolled component adalah alternatif lain dari controlled component, dimana data form akan ditangani oleh DOM-nya sendiri. Untuk menulis uncontrolled component, alih-alih menulis event handler untuk setiap pembaruan state, kita bisa menggunakan ref untuk mendapatkan nilai form dari DOM.
    Karena hal ini, terkadang lebih mudah untuk mengintegrasikan kode React dan non-React jika menggunakan uncontrolled component. Ini berarti lebih sedikit kode jika kita menginginkan solusi cepat walau tak rapi. Selain itu pada umumnya kita harus menggunakan controlled component.

## Kesimpulan
Form controlled dan uncontrolled memiliki kelebihannya sendiri. Kita perlu mengevaluasi situasi kita secara spesifik dan memilih pendekatan apa yang cocok untuk kondisi kita.

Jika formulir sangat sederhana dalam hal umpan balik UI, uncontrolled dengan refs sepenuhnya baik-baik saja. Kita tidak perlu mendengarkan apa yang dikatakan berbagai artikel bahwa uncontrolled itu "buruk". Lagipula kita selalu dapat bermigrasi ke controlled input.

# Uraian Praktikum
Membuat formulir pendaftaran. dimana formulir tersebut memiliki ketentuan seperti contoh pada field nama wajib diisi dan hanya menerima inputan huruf, untuk field nomor handphone wajib diisi yang inputannya adalah angka dan panjang karakternya 9-14, dan masih banyak lagi. jika inputan tidak sesuai ketentuan maka akan muncul error

