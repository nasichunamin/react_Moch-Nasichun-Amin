# Resume Clean Code

## Clean Code
Clean Code merupakan istilah untuk kode yang mudah dibaca, dipahami dan diubah oleh programmer
Mengapa clean code? 
- Work Collaboration : semua orang harus bisa apa yang kita kerjakan
- Feature Development : agar semua orang mengetahui fungsi fungsi atau fitur fitur yang ada dalam code. 
- Faster Development : karena adanya clean code semua orang bisa lebih memahami code dengan cepat dan dapat bekerja dengan cepat

## Karakteristik Clean Code
- penamaan mudah dipahami
- mudah dieja dan dicari
- singkat namun mendeskripsikan konteks
- konsisten
- hindari penambahan konteks yang tidak perlu
- komentar
- good function
- gunakan konvensi (menggunakan style guide yang ada)
- formatting, 
<br /> adapun saran formatting yaitu:
  * lebar baris code 80-120 karakter
  * satu class 300-500 baris
  * baris code yang berhubungan saling berdekatan
  * dekatkan fungsi dengan pemanggilnya
  * deklarasi variabel berdekatan dengan penggunanya
  * perhatikan indentasi
  * menggunakan prettier atau formatter

## Clean Code Principle
Clean code memiliki 2 principle yaitu : KISS and DRY
- KISS -> Keep It So Simple
hindari membuat fungsi yang dibuat untuk melakukan A, sekaligus memodifikasi B, mengecek fungsi C, dst.
Tips untuk selalu KISS adalah
  * fungsi atau class harus kecil
  * fungsi dibuat untuk melakukan satu tugas saja
  * jangan gunakan terlalu banyak argumen pada fungsi
  * harus diperhatikan untuk mencapai kondisi yang seimbang, kecil, dan jumlahnya minimal.

- DRY -> Don't Repeat Yourself
Duplikasi code terjadi karena sering copy paste. untuk menghindari duplikasi code buatlah fungsi yang dapat digunakan secara berulang - ulang.

## Refactoring
Refactoring adalah proses restrukturisasi kode yang dibuat, dengan cara mengubah struktur internal tanpa mengubah perilaku eksternal. prinsip kiss dan dry bisa dicapai dengan cara refactor.
teknik refactoring :
- membuat sebuah abstraksi
- memecah kode dengan fungsi/class
- perbaiki penamaan dan lokal kode
- deteksi kode yang memiliki duplikasi

# Uraian Praktikum
Pada tugas praktikum clean code ada 2 problem. pada problem pertama kita disuuh menganalisis ada berapa kesalahan yang ada di dalam code tersebut beserta alasan mengapa code tersebut salah. Problem ke 2 kita disuruh me-rewrite code dan membuat code tersebut tidak ada error