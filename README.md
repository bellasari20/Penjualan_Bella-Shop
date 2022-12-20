Selamat datang!
Github ini digunakan untuk belajar demi memenuhi UAS mata kuliah Analisis Desain Sistem. 
Sebelum memindahkan database siapkan beberapa aplikasi, yaitu:
•	XAMPP
•	Composer Install
•	Gitbash

Langkah-langkah memindahkan database dari github dengan gitbash
1.	Buka xampp lalu start apache dan mysql, klik admin di mysql lalu php myadmin
2.	buka github.com cari file yang anda inginkan
3.	buat folder di C
4.	klik kanan kemudiaan open with git bash
5.	ketik: git clone (link yg dicopy dari git.hub.com)
6.	cd (nama file dalam folder)
7.	Composer install
8.	klik file lalu cari envyexample lalu di copy paste lalu ganti nama jadi env
9.	Klik envy menggunakan notepad plus plus
10.	Buka phpmyadmin buat file baru sesuai nama file di env database
11.	Php artisan migrate
12.	Php artisan db:seed
13.	Php artisan key:generate
14.	Php artisan serve
15.	muncul sendiri di php myadmin
16.	eksport data tersebut.
