# Resume React Fundamental

## JSX
JSX (Javascript XML) merupakan ekstensi syntax dari javascript yang penggunaannya sangat disarankan di react karena menggambarkan apa yang seharusnya tampak dari user interface. Nah, dari JSX sendiri nanti akan menghasilkan react element.<br/>

Kenapa menggunakan JSX?
* JSX dibuatkan berdasarkan fakta kalau logika rendering sangat terikat dengan logic UI.
* Separation of Technology -> Separation of Concerns.
Dengan menggunakan JSX kita bisa menggabungkan dengan html dan CSS.<br/>

JSX vs React.createElement
- kita tidak perlu menggunakan JSX, tapi JSX memudahkan kita menulis aplikasi React.
- Syntatic Sugar dari fungsi React.createElement(component, prop, ...children).<br/>

Spesifikasi jenis elemen React
- Kapitalisasi untuk komponen react.
- Huruf kecil (lowercase) untuk komponen bawaan.<br/>

## React Component
Komponen React adalah bagian kode yang dapat digunakan kembali yang digunakan untuk menentukan tampilan, behavior, dan state sebagian UI.

## Komposisi komponen dan props
Apa itu Props?<br/>
* Singkatan dari properties, membuat kita dapat memberikan argumen atau data pada component.
* Props membantu untuk mebuat komponen menjadi lebih dinamis
* Props dioper ke component sama seperti memberikan atribut pada tag HTML
* Props pada component adalah read-only dan tidak dapat diubah
  
## React Lifecycle
React Lifecycle atau siklus hidup pada komponen raect. React lifecycle adalah sederetan event yang terjadi dari awal komponen muncul sampai komponen itu hilang.<br/>
React Lifecycle dibagi menjadi 3 yaitu :
* Mounting
* Updating
* Unmounting<br/>
Lifecycle method yang umum :
* render()
  * Fungsi yang paling sering dipakai
  * Required pada class component
  * Pure function. tidak boleh ada setState()
* componentDidMount()
  *  Dipanggil ketika component sudah di render untuk pertama kali.
  *  Tempaat yang tepat untuk pemanggilan API
  *  Boleh ada setState().
* componentDidUpdate()
  * Dipanggil ketika terjadi update (props atau state berubah) 
* componentWillUnmount()
  * Dipanggil ketika component akan dihancurkan
  * cocok untuk clean up actions.
<br/>
Lifecycle method yang lainnya 
* shouldComponentUpdate()
* Static getDerivedStateFromProps()
* getSnapshotBeforeUpdate()

## Conditional
* Render Bersyarat
  Pada React, kita dapat membuat komponen berbeda yang mencakup perilaku yang dibutuhkan. Lalu, kita dapat me-render hanya beberapa bagian saja, berdasarkan state dari aplikasi anda.
  * Menggunakan If
  * Inline If dengan operator &&
  * Inline If-Else dengan ternary conditional operator
  * Mencegah komponen untuk rendering
* Render List
  Kita dapat membangun koleksi dari beberapa elemen dan menyertakan dalam JSX menggunakan tanda kurung kurawal{}
* Key
  Key membantu React untuk mengidentifikasi item mana yang telah diubah, ditambahkan, atau dihilangkan.

## Directory Structure
React tidak memiliki pendapat tentang bagaimana cara memasukkan file ke folder.
* Cara pertama : Pengelompokan berdasarkan fitur atau rute
* Pengelompokan berdasarka jenis file
<br/>
Beberapa tips react mengenai bagaimana cara kita menentukan nest structure:
* Hindari terlalu banyak nesting
* Jangan terlalu memikirkannya

## Styling
Ada 3 cara styling yaitu :
* Classes dan CSS
* Atribut Style
* Modul CSS

# Uraian Praktikum
Membuat todo list dengan memiliki 3 field yaitu id(number), name(string), dan completed(boolean). apabila completed bernilai "True" maka nama todo-nya akan tercoret.

