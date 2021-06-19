NAMA : Rivaldi Hamzah
NIM : 311910656

Buat folder baru dengan nama lab11_php_ci pada docroot webserver (htdocs)
![image](https://user-images.githubusercontent.com/56198396/122627747-afc0de80-d0db-11eb-96ab-01aba1c42752.png)

Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini
![image](https://user-images.githubusercontent.com/56198396/122627750-bcddcd80-d0db-11eb-9567-9c324ed39279.png)

Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.
![image](https://user-images.githubusercontent.com/56198396/122627756-ca935300-d0db-11eb-925e-844e7e625f71.png)


Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.
![image](https://user-images.githubusercontent.com/56198396/122627767-e0a11380-d0db-11eb-86b5-5b8f184307c1.png)

Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah: ( php spark )
![image](https://user-images.githubusercontent.com/56198396/122627773-ee569900-d0db-11eb-8f10-4abe61870333.png)

Ketika terjadi error pada aplikasi akan ditampilkan pesan kesalahan seperti berikut.
![image](https://user-images.githubusercontent.com/56198396/122627782-ff070f00-d0db-11eb-97d8-cad32e382ed8.png)

Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable CI_ENVIRINMENT menjadi development
![image](https://user-images.githubusercontent.com/56198396/122627790-10501b80-d0dc-11eb-8e65-f7b26cce909d.png)

Contoh error yang terjadi. Untuk mencoba error tersebut, ubah kode pada file app/Controller/Home.php hilangkan titik koma pada akhir kode.
![image](https://user-images.githubusercontent.com/56198396/122627796-1a721a00-d0dc-11eb-8c51-d3f538cc7915.png)

Router terletak pada file app/config/Routes.php
![image](https://user-images.githubusercontent.com/56198396/122627802-2958cc80-d0dc-11eb-9c0d-b13da2f6ea36.png)

Selanjutnya coba akses route yang telah dibuat dengan mengakses alamat url http://localhost:8080/about
![image](https://user-images.githubusercontent.com/56198396/122627818-3ecdf680-d0dc-11eb-888b-90d8c469039b.png)

Selanjutnya adalah membuat Controller Page. Buat file baru dengan nama page.php pada direktori Controller kemudian isi kodenya seperti berikut.
![image](https://user-images.githubusercontent.com/56198396/122627824-4a212200-d0dc-11eb-840e-3185a279fe03.png)

Tambahkan method baru pada Controller Page seperti berikut.
![image](https://user-images.githubusercontent.com/56198396/122627827-56a57a80-d0dc-11eb-95e7-1e47fa0dc304.png)

Method ini belum ada pada routing, sehingga cara mengaksesnya dengan menggunakan alamat: http://localhost:8080/page/tos
![image](https://user-images.githubusercontent.com/56198396/122627835-658c2d00-d0dc-11eb-8739-19b5d8dc02cd.png)

Buat file css pada direktori public dengan nama style.css
![image](https://user-images.githubusercontent.com/56198396/122627844-7177ef00-d0dc-11eb-97a0-0d3932cd0990.png)

Kemudian buat folder template pada direktori view kemudian buat file header.php dan footer.php
![image](https://user-images.githubusercontent.com/56198396/122627851-7b99ed80-d0dc-11eb-95b5-b4e047af69e6.png)

footer.php
![image](https://user-images.githubusercontent.com/56198396/122627858-86548280-d0dc-11eb-9535-93cc8e8fe484.png)

Kemudian ubah file app/view/about.php seperti berikut
![image](https://user-images.githubusercontent.com/56198396/122627865-910f1780-d0dc-11eb-984a-3355d22c3d4d.png)

selanjutnya refresh tampilan tersebut:
![image](https://user-images.githubusercontent.com/56198396/122627877-9a987f80-d0dc-11eb-80e3-7e19f7c40360.png)
