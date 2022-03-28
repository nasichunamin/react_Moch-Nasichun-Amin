# Resume React Routing

## Routes
Router merupakan modul dalam react yang berfungsi untuk melakukan proses navigasi pada SPA(Single Page Application).<br/>
Single Page Application vs Multi Page Application <br/>
Multipage Application(MPA) juga disebut dengan tradisional web app adalah jenis aplikasi website dimana perlu memuat ulang seluruh halaman web setiap kali membuat permintaan baru.<br/>

Single Page Application(SPA) adalah salah satu jenis aplikasi website dimana hanya ada 1 halaman yang menangani semua aktivitas yang terjadi dalam aplikasi tersebut.

## Use URL params in react
Parameter URL adalah suatu parameter yang nilainya ditetapkan secara dinamis di URL halaman.<br/>

Perbedaan Link dan Redirect <br/>
Link : 
* Dapat digunakan pada kondisi apapun.
* memberikan history baru pada browser.
* Bereaksi dengan click seperti a href.
<br/>

Redirect :
* Lebih sering digunakan pada halaman 404.
* Menimpa history pada browser.
* Bereaksi dengan suatu kondisi.

## Hook Routing React
* useHistory
  Memberi kita akses ke instance riwayat yang dapat digunakan untuk bernavigasi. contoh :
  * length -> jumlah entri dalam tumpukan riwayat (angka)
  * go -> Memindahkan penunjuk di tumpukan riwayat sebanyak n entri(fungsi)
  * goBack -> setara denan go(-1) (fungsi)
  * goForward -> setara dengan go(1) (fungsi)
  * Push -> Mendorong entri baru ke tumpukan riwayat (fungsi)
  * replace -> Mengganti entri saat ini di tumpukan riwayat history(fungsi)
* useLocation 
  Mengembalikan objek lokasi yang mewakili URL saat ini. kita dapat memikirkannya seperti useState yang mengembalikan lokasi baru, setiap kali URL berubah.
* useParams
  Mengembalikan objek pasangan kunci/nilai parameter URL. Gunakan untuk mengakses match.params dari route saat ini.
* useRouteMatch
  Mencoba mencocokkan URL saat ini dengan cara yang sama seperti Route. Ini sebagian besar berguna untuk mendapatkan akses ke data kecocokan tanpa benar benar merender Route.

# Uraian Praktikum
melanjutkan tugas praktikum react hooks dengan menambahkan menu dengan react routing. dimana menu tersebut ada about, about-app, about-author, dan page not found,