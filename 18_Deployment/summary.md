# Resume Deployment

## Build React App
Secara default, React mengandung banyak pesan peringatan. Peringatan-peringatan ini sangat berguna dalam pengembangan aplikasi. Namun, pesan-pesan ini membuat React menjadi lebih besar dan lambat. Oleh karenanya kita harus menggunakan versi produksi ketika men-deploy aplikasi.<br>

Tujuan melakukan build agar aplikasi kita menjadi versi production, sehingga performanya lebih ringan cepat. Kita mem-build aplikasi react kita menggunakan "npm react build" (jika menggunakan npm). Untuk menjalankan aplikasi yang optimal di lokal komputer, bisa menggunakan serve.

## Deployment
Deployment adalah kegiatan yang bertujuan untuk menyebarkan aplikasi yang sudah kita buat. Harapannya aplikasi tersebut dapat diakses oleh banyak orang, tidak hanya oleh kita sendiri.

## Deployment dengan Surge dan Netlify CLI
Surge adalah layanan penerbit website statik (static web publishing) gratis untuk Front-End Developers. Website statik yang menggunakan surge akan memiliki subdomain *.surge.sh. Surge dapat menerima file HTML, CSS, dan JS. Untuk menginstall Surge bisa dengan cara "npm install --global surge". setelah proses installasi jalankan perintah "surge" di terminal. Pada surge terdapat Teardown Surge, teardown surge ini digunakan jika kita tidak ingin mempublikasikan sebagian domain atau sbdomain, caranya dengan ketik di terminal "surge teardown vancouver.surge.sh".

---

Netlify adalah salah satu platform penyedia layanan build tools sekaligus Continous Deployment. Netlify memungkinkan kita untuk mempublish website statis secara gratis. Netlify juga sudah terintegrasi dengan Git Host popular seperti Github, Gitlab dan Bitbucket. untuk mendeploy dengan netlify kita harus membuat akun terlebih dahulu di web netlify, lalu setelah membuat kita bisa install dengan cara "npm install netlify-cli -g".

# Uraian Praktikum
Membuat react project basic yang dirubah sedikit lalu di deploy menggunakan surge/netlify.

