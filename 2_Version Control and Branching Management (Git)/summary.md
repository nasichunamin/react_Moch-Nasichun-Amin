# Resume Version Control and Branching Management (Git)

## Version Control
* Versioning adalah mengatur versi dari source code program.
* Untuk mengeteks sebuah revisi ada beberapa macam yaitu version control sistem (VCS), Source Code Manager (SCM), Revision Control System (RCS).
* Sejarah VCS :
    * Single user -> di tahun pengembangan unix untuk memanajemen sebuah tugas masih bersifat localize karna internet belum seperti sekarang. disini menggunakan SCSS.
    * Centralized -> lalu muncul internet atau centralized. centralized ini naik level lagi dari yang sebelumnya localized sekarang centralized. centralized itu sdh ada sebuah sistem terpusat mungkin di internet atau server lokal, jadi misal ada 3 atau 5 developer yang centralized, mengedit 1 project di server. server ini bisa ngubah langsung. jadi sangat tergantung dengan server, jika server ini mati maka para developer tidak bisa mengedit project tersebut.
    * Distributed -> yang paling banyak digunakan sekarang ini yaitu git, dimana git ini merupakan distributed sistem. intinya kalau kita memakai git kita punya keduanya, di local ada dan di server juga ada. jadi kita ngeditnya di local tapi sudah terkoneksi ke server.
## GIT
  * Git adalah sebuah salah satu VCS populer yang digunakan developer untuk mengembangkan software secara bersama - sama.
  * Terdistribusi bukan tersentralisasi. terdistribusi artinya kita memiliki beberapa komputer tapi saling terkoneksi, nah untuk menghubungkan itu kita pake git. tapi bukan tersentralisasi atau terpaku dengan server/pusat.
  * Contoh secara diagram ada beberapa developer dan terkoneksi dengan remote komputer/server. Remote / server tersebut dijadikan pusat / synchronize yang memiliki git.
  * Git akan mengetrack semua perubahan kapanpun dia berubah dan siapa yang merubah. Di git ada commit yang digunakan sebagai riwayat perubahan.
  * Git yang sudah public salah satunya github. gitbuh merupakan salah satu social medianya para developer. disana ada git server yang menampung repository project kita.
  * Syncronize adalah mengaitkan source code kita dengan github.
## Branching
  * Branching adalah mengisolasi perubahan perubahan yang ada dalam project.
  * Workflow collaboration adalah bagaimana alur dari menggunakan github dari situ nanti kita bisa tahu optimasinya seperti apa
  * Branch master jangan diubah ubah, master ini digunakan untuk yang sudah final. untuk development mengumpulkan semua fitur tambahan yang nantinya akan dimerge ke branch master.

# Uraian Essay / Praktikum
Untuk tugas praktikum, disini saya menggunakan project html sederhana. Disini saya mencoba membuat web upin ipin sederhana, dimana di file pertama, web hanya berisi deskripsi singkat tentang upin ipin. Untuk file kedua web tersebut saya tambahkan fitur hyperlink, disitu saya memasukkan link youtube let's copaque dimana link tersebut akan menujut youtube film upin ipin. File ketiga saya menambahkan fitur gambar diatas deskripsi upin ipin.  
Selanjutnya, saya membuat branch master sesuai tugas praktikum, lalu membuat branch develop dimana branch tersebut saya isi dengan file html web yang berisi deskripsi singkat tadi. Lalu, saya membuat lagi branch "penambahan fitur 1", didalam branch ini saya menambahkan file html yang sudah ditambahkan link youtube tadi, dan yang ketiga saya membuat branch "penambahan fitur 2", di branch ini saya menambahkan file html yang sudah ditambahkan gambar upin ipin. setelah membuat semua branch saya pull & request branch "penambahan fitur 1" dan "penambahan fitur 2" ke branch develop, lalu saya merge branch "penambahan fitur 1" dan "penambahan fitur 2" ke branch develop.

