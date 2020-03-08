1. siapkan webserver seperti xampp dan lain lain
2. code igniter dan library REST API. 
3. download rest api pada link ini https://github.com/ardisaurus/ci-restserver. lalu copy semua isinya pada folder yang akan kita gunakan
4. setelah itu download postman agar mempermudah kita dalam penggunaan REST API
5. masukkan 127.0.0.1/rest_ci/index.php/kontak pada postman. apabila akan menggunakan metode get maka kita tinggal pilih get pada pilihan yang ada di sebelah link.
6. get berfungsi untuk mengambil/menampilkan data
7. lalu kita akan menggunakan post dengan cara mengganti pilihan get menjadi Post.lalu ada menu bar di bawah link. klik body lalu pilih x-www-form-urlencoded
8. kita deklarasikan key kita dan value yang akan kita masukkan. 
9. setelah kita selesai mendeklarasikan key yang sesuai dengan database maka kita isi value
10. klik send untuk menginput data ke database. untuk melihat apakah data kita telah masuk kita gunakan metode get seperti diatas tadi
11. put. put disini berfungsi untuk mengambil data dan mengupdate data.
12. saat akan menggunakan put kita harus mengerti id data yang akan kita ubah. lalu setelah mengerti,maka ubah data sesuai keinginan. apabila selesai kita klik send
13. untuk cek apakah data telah terupdate kita gunakan metode get lagi
14. delete. delete berfungsi untuk menghapus data berdasarkan id. 
15. nsaat akan mendelete data kita harus mengerti id data yang akan kita delete. lalu caranya seperti metode post hanya saja yang diisi hanya id saja.
16 setelah kita isi idnya maka kita klik send. data telah dihapus.
17. untuk melihat apakah data kita telah terhapus maka kita gunakan metode get untuk mengecek data kita