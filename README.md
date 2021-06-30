# lab11_php_ci
Membuat Database: Studi Kasus Data Artikel, Membuat Database dan juga Membuat Tabel
![Screenshot_1](https://user-images.githubusercontent.com/52759649/123571726-0c677c00-d7f5-11eb-93af-789198cddb3e.jpg)
Konfigurasi koneksi database, disini saya menggunakan cara merubah data yaitu pada file app/config/database.php dikarenakan menggunakan file .env tidak bisa.
![Screenshot_2](https://user-images.githubusercontent.com/52759649/123571822-4173ce80-d7f5-11eb-8f88-eb95a7993b48.jpg)
![Screenshot_7](https://user-images.githubusercontent.com/52759649/123572186-f1493c00-d7f5-11eb-83f1-92392c9db4e5.jpg)
Membuat Model, Selanjutnya adalah membuat Model untuk memproses data Artikel. Buat file baru pada direktori app/Models dengan nama ArtikelModel.php
![Screenshot_3](https://user-images.githubusercontent.com/52759649/123571902-67996e80-d7f5-11eb-989d-476d79ecc523.jpg)
Membuat Controller, Buat Controller baru dengan nama Artikel.php pada direktori app/Controllers.
![Screenshot_4](https://user-images.githubusercontent.com/52759649/123571968-8a2b8780-d7f5-11eb-8f81-31079e4f3706.jpg)
Membuat View,Buat direktori baru dengan nama artikel pada direktori app/views, kemudian buat file baru dengan nama index.php. 
![Screenshot_5](https://user-images.githubusercontent.com/52759649/123572023-9f081b00-d7f5-11eb-9551-849a4835f2a2.jpg)
tambahkan beberapa data pada database agar dapat ditampilkan datanya.
![Screenshot_6](https://user-images.githubusercontent.com/52759649/123572086-be06ad00-d7f5-11eb-996c-85e79a81602b.jpg)
Membuat Tampilan Detail Artikel, Tampilan pada saat judul berita di klik maka akan diarahkan ke halaman yang berbeda. Tambahkan fungsi baru pada Controller Artikel dengan nama view().
![Screenshot_8](https://user-images.githubusercontent.com/52759649/123572216-002fee80-d7f6-11eb-8862-438715e80124.jpg)
Membuat View Detail, Buat view baru untuk halaman detail dengan nama app/views/artikel/detail.php
![Screenshot_9](https://user-images.githubusercontent.com/52759649/123572276-23f33480-d7f6-11eb-91c0-ebe3dba94887.jpg)
Membuat Routing untuk artikel detail, Buka Kembali file app/config/Routes.php, kemudian tambahkan routing untuk artikel detail.
![Screenshot_10](https://user-images.githubusercontent.com/52759649/123572398-569d2d00-d7f6-11eb-8e22-f83bf4da8f24.jpg)
![Screenshot_11](https://user-images.githubusercontent.com/52759649/123572462-7a607300-d7f6-11eb-9633-1a7fb0064d75.jpg)
Membuat Menu Admin, Menu admin adalah untuk proses CRUD data artikel. Buat method baru pada Controller Artikel dengan nama admin_index(). 
![Screenshot_12](https://user-images.githubusercontent.com/52759649/123572516-8ea47000-d7f6-11eb-85a5-84b741debe20.jpg)
Selanjutnya buat view untuk tampilan admin dengan nama admin_index.php
![Screenshot_18](https://user-images.githubusercontent.com/52759649/123572711-d6c39280-d7f6-11eb-8cd3-1cf88c4ea502.jpg)
Tambahkan routing untuk menu admin seperti berikut:
![Screenshot_13](https://user-images.githubusercontent.com/52759649/123572587-abd93e80-d7f6-11eb-865f-150ba2e74dc7.jpg)
Menambah Data Artikel, Tambahkan fungsi/method baru pada Controller Artikel dengan nama add(). 
![Screenshot_19](https://user-images.githubusercontent.com/52759649/123573320-ebecf100-d7f7-11eb-94e0-d43238a4de1f.jpg)
Kemudian buat view untuk form tambah dengan nama form_add.php
![Screenshot_20](https://user-images.githubusercontent.com/52759649/123573336-f0b1a500-d7f7-11eb-9ae9-c670b0484291.jpg)
Mengubah Data, Tambahkan fungsi/method baru pada Controller Artikel dengan nama edit().
![Screenshot_21](https://user-images.githubusercontent.com/52759649/123573617-7df4f980-d7f8-11eb-8e75-932cf7112ca3.jpg)
Kemudian buat view untuk form tambah dengan nama form_edit.php
![Screenshot_22](https://user-images.githubusercontent.com/52759649/123573640-877e6180-d7f8-11eb-8ab5-c9a592a0e09b.jpg)
Menghapus Data,Tambahkan fungsi/method baru pada Controller Artikel dengan nama delete(). 
![Screenshot_17](https://user-images.githubusercontent.com/52759649/123573723-a5e45d00-d7f8-11eb-808c-958fab47e9b0.jpg)
jika tidak sesuai dengan hasilnya saya mohon maaf karena saya memang mengerjakan tugas ini sendiri, dimohon untuk melihat detail pada ss karena bisa saja dengan copy paste gambar.
