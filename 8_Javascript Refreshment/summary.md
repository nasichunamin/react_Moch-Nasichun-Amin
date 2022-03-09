# Resume Javascript refreshment

## Javascript
Javascript adalah Bahasa Pemrogaman yang tingkat tinggi (high-level), scripting, untyped dan interpreted.
javascript itu dibuat untuk halaman web, apapun itu web browsernya. javascript merupakan bahasa yang untype atau tidak berpengaruh terhadap tipe data, dan yang terakhir interpreted, selama kita mempunyai web browser javascript bisa dijalankan karena memiliki bahasa yang fleksibel dan mudah untuk diuji.

## Declaration, Scoping, Hoisting
### Declaration
Declaration adalah proses pembuatan data variabel untuk menyimpan data.
ada 3 cara untuk pendeklarasian variabel yaitu :
* Var -> pada umumnya var jarang digunakan, sebenarnya kegunaannya hampir sama dengan let dengan beberapa perbedaan.
* Let -> digunakan saat kita membutuhkan nilai yang dapat diubah
* Const -> digunakan saat kita membutuhkan nilai yang tidak bisa di "reassign". maksud reassign adalah tidak bisa memberikan nilai baru saat variabel const tersebut sudah memiliki nilai sebelumnya.

### Scoping
Scoping adalah menentukan dimana variabel, fungsi, dan objek diatur dan dapat diakses dalam kode kita, yang berarti ruang lingkup variabel dikendalikan oleh lokasi deklarasi variabel.
ada 3 macam scoping yaitu :
* global scop -> saat kita mendeklarasikan variabel, variabel tersebut dapat diakses untuk setiap kondisi saat kita koding.
* function/local scop -> pendeklarasian variabel didalam function, namun variabel tersebut tidak dapat diakses diluar function tersebut.
* block scop -> untuk block scop, ini berkaitan dengan tanda kurung kurawal({}), setiap ada buka tutup kurung kurawal itu yang disebut block. jadi, saat pendeklarasian variabel didalam block scop, yang dapat diakses diluar block scop hanya variabel var saja, selain variabel var seperti let dan const tidak dapat diakses diluar scop.
  
### Hoisting
Hoisting adalah membuat beberapa jenis variabel atau fungsi yang dapat diakses/digunakan dalam kode sebelum dideklarasikan.
* Deklarasi var dan function adalah hoisted, oleh karena itu mereka dapat digunakan bahkan sebelum deklarasi itu sendiri terjadi.jadi untuk var kita bisa berikan nilai dulu variabelnya baru kita inisialisasi var nya. dan untuk function kita bisa panggil dulu fungsi nya lalu kita bisa buat functionnya.
* sedangkan let dan const tidak hoisted karena itu mereka tidak dapat digunakan bahkan sebelum deklarasi terjadi. jadi, let dan const harus di inisialisasi terlebih dahulu setelah itu kita console.
  
Jadi kesimpulannya :
* var -> bisa di deklarasi, redeklarasi, reassignment, hoisting, global scope, dan block scope.
* let -> bisa di deklarasi,reassignment, dan global scope.
* cons -> hanya bisa global scope.

## Values and References
Javascript memiliki 2 kategori tipe data yaitu primitives dan objek.
* Primitives dalam pemrograman adalah unit pemrosesan terkecil dan elemen paling sederhana yang tersedia dalam bahasa pemrograman.
contoh tipe data primitives : String, Boolean, Number, BigInt(ES11), Undefined, Null, Symbol(ES6)
* Objects adalah unit yang menyimpan properti dan fungsi(method)
contoh tipe data objects : Object, Array, Function, Date, Set, Map, Weak Set, Weak Map.

Jadi, values memiliki aturan sederhana, untuk meneruskan nilai adalah bahwa semua nilai primitif dalam javascript diteruskan oleh nilai
sedangkan reference, jika kita meneruskan references bagaimanapun, akan memberikan references yang sama.

## Destructuring dan Spread Syntax
### Destructuring
Destructuring adalah ekspresi dari javascript yang memungkinkan untuk menyalin nilai dari array, atau properti dari objek ke dalam variabel yang berbeda
tugas destructuring ini adalah menyalin,
untuk array sendiri itu menyalin elemen" dalam array kedalam variabel baru.

### Spread syntax
Spread syntax dapat digunakan ketika semua elemen dari object atau array perlu dimasukkan ke dalam semacam daftar.

## Method
Method merupakan sebuah fungsi yang terkait dengan object, membuat programnya se-sederhana mungkin sesuai kegunaan masing - masing.
* concat -> menggabungkan 2 atau lebih array, dan mengembalikan salinan array yang digabungkan.
* Map -> membuat array baru dengan hasil memanggil fungsi untuk setiap elemen array.
* Foreach -> memanggil fungsi array untuk setiap elemen array.
* Slice -> Memilih bagian dari array, dan mengembalikan array baru.
* Filter -> Membuat array baru dengan setiap elemen dalam array yang lulus seleksi.
* Reduce -> Melakukan operasi pada setiap elemen array menjadi nilai tunggal(dari kiri ke kanan).

## Control Flow
* Normal flow -> pengeksekusian statement dari atas ke bawah atau kiri ke kanan yang dilakukan secara. berurutan
* Control flow -> mengatur alur eksekusi pada statement atau jalannya program sesuai keinginan kita.

## Function
Function di dalam javascript adalah sebuah objek. karena memiliki properti dan juga method.
function digunakan untuk melakukan serangkaian komputasi/prosedur yang dapat digunakan berulang kali.

## Async await
* Synchronous -> mengeksekusi setiap perintah satu per satu sesuai urutan kode yang dituliskan
* Asynchronous -> hasil eksekusi atau output tidak selalu berdasarkan urutan kode, tetapi berdasarkan waktu proses

## Callback
Callback adalah fungsi yang dikirimkan sebagai parameter pada fungsi lain atau
Callback adalah fungsi yang dieksekusi setelah fungsi lain selesai dijalankan.

## Promise
Promise adalah ojek yang merepresentasikan keberhasilan atau kegagalan pada sebuah event yang asyncronous dimasa mendatang
