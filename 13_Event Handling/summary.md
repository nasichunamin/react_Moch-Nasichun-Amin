# Resume Event Handling

## State
State adalah data private sebuah component. Data ini hanya tersedia untuk component tersebut dan tidak bisa diakses dari component lain. Berikut beberapa poin mengenai state :
* Data yang bisa dimodifikasi menggunakan setState
* Setiap terjadi modifikasi akan terjadi render ulang
* Bersifat Asynchronous
* Dipakai dalam class
<br/>

Perbedan Props dan State ialah.<br>
Props :
* Props are read-only
* props can not be modified
<br>

State :
* State changes can be asynchronous
* statecan be modified using this.setState
  
## Statefull & Stateless
* Statefull component adalah komponen yang memiliki state. komponen ini dibuat dengan class. Kelebihan dari class component adalah memiliki lifecycle.
* Stateless Component adalah komponen yang tidak memiliki state hanya prop. Umumnya component ini dibuat dengan function karena codenya lebih ringkas.
<br>

Komponen statefull dan stateless memiliki banyak nama berbeda. Mereka juga dikenal sebagai :
1. Smart component & Dump component
2. Container component & Presentational component
<br>

Perbedaan Komponen statefull dan komponen stateless.
Stateless component :
* Tidak tahu tentang aplikasi
* tidak melakukan data fetching(pengembalian data)
* tujuan utamanya adalah visualisasi
* dapat digunakan kembali
* hanya berkomunikasi dengan induk langsungnya.
  
<br>

Statefull component :
* mengerti tentang aplikasi
* melakukan data fetching
* berinteraksi dengan aplikasi
* tidak dapat digunakan kembali
* meneruskan status dan data ke anak anaknya.

## Handling Event
Handling Event adalah suatu metode ntuk menangani sebuah event atau aksi yang diberikan pengguna kepada suatu komponen.<br>
Event adalah suatu peristiwa yang dipicu oleh pengguna pada suatu komponen, misalnya tombol ditekan.
<br>

Beberapa Contoh list event:
1. Clipboard Events (Promise terpenuhi)
2. Form Events (onChange, onSubmit)
3. Mouse Events (onClick, onDoubleClick, onMouseOver)
4. Generic Events (onError, onLoad)


# Uraian Praktikum
Membuat daftar pekerjaan yang bisa menambahkan inputan, didalamnya terdapat checklist pada setiap daftar pekerjaan (checklist diaktifkan jika checklist selesai dikerjakan), dan ada fitur hapus suatu pekerjaan.