Finansialku adalah aplikasi opens source yang dikembangkan untuk mencatat problem keuangan, seperti keuangan masuk / debit dan keuangan keluar / credit. Beberapa fitur diantaranya:

- Daftar (Development)
- Masuk / Login
- Lupa Password (Development)
- Dashboard
- Kategori Uang Masuk
- Uang Masuk
- Kategori Uang keluar
- Uang keluar

UANGKU juga akan dibuat versi native android, yang rencana akan di kembangkan dengan android studi / java.
Untuk versi webnya menggunakan Framework Laravel


## Screenshot

- Login
<img src="https://i.imgur.com/3lfDm0L.png" style="width:100%">

- Register
<img src="https://i.imgur.com/vLeOxNn.png" style="width:100%">

- Dashboard
<img src="https://i.imgur.com/NDK9qua.png" style="width:100%">

- Uang Masuk
<img src="https://i.imgur.com/MAegGDC.png" style="width:100%">

- Laporan Uang Masuk
<img src="https://i.imgur.com/aPv4II6.png" style="width:100%">

## Cara Install

`$ > git clone https://github.com/maulayyacyber/uangku-laravel.git`

`$ > cd uangku-laravel`

`$ > composer install`

`$ > cp env.example .env`

silahkan konfigurasi pengaturan database, seperti host, user, password dan nama database

`$ > composer dump-autoload`

`$ > php artisan migrate`

`$ > php artisan db:seed`


USERNAME : admin

PASSWORD : admin

## Cara Menjalankan

`$ > cd uangku-laravel`

`$ > php artisan serve`

Silahkan buka browser dan ketikkan : http://localhost:8000

