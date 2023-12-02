<p align="center"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></p>
<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Cara Install Project DENGAN github desktop
Untuk menginstal project ini anda harus memiliki Composer
bagi yang belum install composer silahkan download [Klik di sini](https://getcomposer.org/download/1.9.0/composer.phar) tutorial cara instal composer [klik di sini](https://www.malasngoding.com/cara-install-composer/)

Bagi yang sudah memiliki composer silahkan ikuti tutor dibawah ini
- Klik tombol Clone or download
- Klik Open in desktop
- Klik open GithubDesktop.exe
- Silahkan pilih lokasi path yang anda inginkan
- Kemudian klik Clone
- Tunggu sampai proses clone selesai
- Buka folder porject yang sudah di clone melalui terminal
- Lakukan composer install ketik
```terminal
composer install
```
- Tunggu sampai proses selesai
- Buat database baru di phpmyadmin anda beri nama sesuka hati anda
- Copy file .env.example yang ada di dalam folder project dan ubah namanya menjadi .env
bagi yang menggunakan git bash atau terminal linux bisa ketik seperti dibawah
```terminal
cp .env.example .env
```
bagi yang menggunakan terminal windows bisa ketik seperti dibawah
```terminal
copy .env.example .env
```
- Lakukan generate key ketik 
```terminal
php artisan key:generate
```
- Buka file .env
- Ubah konfigurasi database sesuai nama database yang anda buat tadi lalu simpan
- lakukan migrate ketik :
```terminal
php artisan migrate --seed
```
- kemudian ketik :
```
php artisan storage:link
```
- Finish project laravel bisa dijalankan dengan menggunakan development server dengan cara ketik
```terminal
php artisan serve
```
- Lalu ctrl+klik pada http://127.0.0.0:8000

## Cara instal project TANPA github desktop
Bagi yang sudah memiliki composer silahkan ikuti tutor dibawah ini
- Klik tombol Clone or download
- Klik download zip
- Silahkan pilih lokasi path yang anda inginkan
- Kemudian klik Oke
- Tunggu sampai proses download selesai
- Extract here 
- Buka folder porject yang sudah di extract dengan terminal
- Lakukan composer install ketik
```terminal
composer install
```
- Tunggu sampai proses selesai
- Buat database baru di phpmyadmin anda beri nama sesuka hati anda
- Copy file .env.example yang ada di dalam folder project dan ubah namanya menjadi .env
bagi yang menggunakan git bash atau terminal linux bisa ketik seperti dibawah
```terminal
cp .env.example .env
```
bagi yang menggunakan terminal windows bisa ketik seperti dibawah
```terminal
copy .env.example .env
```
- Lakukan generate key ketik 
```terminal
php artisan key:generate
```
- Buka file .env
- Ubah konfigurasi database sesuai nama database yang anda buat tadi lalu simpan
- lakukan migrate ketik :
```terminal
php artisan migrate --seed
```
- kemudian ketik :
```
php artisan storage:link
```
- Finish project laravel bisa dijalankan dengan menggunakan development server dengan cara ketik
```terminal
php artisan serve
```
- Lalu ctrl+klik pada http://127.0.0.0:8000

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- [UserInsights](https://userinsights.com)
- [Fragrantica](https://www.fragrantica.com)
- [SOFTonSOFA](https://softonsofa.com/)
- [User10](https://user10.com)
- [Soumettre.fr](https://soumettre.fr/)
- [CodeBrisk](https://codebrisk.com)
- [1Forge](https://1forge.com)
- [TECPRESSO](https://tecpresso.co.jp/)
- [Runtime Converter](http://runtimeconverter.com/)
- [WebL'Agence](https://weblagence.com/)
- [Invoice Ninja](https://www.invoiceninja.com)
- [iMi digital](https://www.imi-digital.de/)
- [Earthlink](https://www.earthlink.ro/)
- [Steadfast Collective](https://steadfastcollective.com/)
- [We Are The Robots Inc.](https://watr.mx/)
- [Understand.io](https://www.understand.io/)
- [Abdel Elrafa](https://abdelelrafa.com)
- [Hyper Host](https://hyper.host)
- [Appoly](https://www.appoly.co.uk)
- [OP.GG](https://op.gg)
- [云软科技](http://www.yunruan.ltd/)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## credit to https://github.com/maulanakevinp/akuntansi

## Flowchart
![flowchart sia drawio](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/1fc3df48-3ba3-4ef0-8d02-46dff38e45c2)
## Desaigner (Database)
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/d443cb6e-d991-4d12-bdd5-9fb4d7e10348)
## Structure 
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/1173d468-2762-4da1-adad-e2eb5b8cbbab)

## 1. Login
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/1bc17177-d75d-4ed0-8808-0184e6507cd7)
## 2. Edit Profile
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/f843543c-fc7a-47fe-a6a2-5a9217a4739f)
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/9f76d489-abf4-4e29-80a4-5aed829cd4e6)
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/77a8d375-d724-42c9-8501-ac4b5a2e9d6e)
## 3. Dashboard
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/9a8c2418-f952-4bf8-b411-ce6f4904d284)

## Jurnal Umum
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/4b6d7b0a-3212-40d2-9f41-ae983b613d53)
## Jurnal Penyesuaian
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/90f04689-4644-4062-9628-48841737f143)
## Buku Besar
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/b2c8ee24-f673-4608-8758-0f61933f6dbe)
## Neraca Lajur
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/62942cbd-aa9c-4466-ab76-d31ec179ff41)
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/07675320-fcd4-43b3-a009-23a557439b7b)

## Laporan Perubahan Ekuitas
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/4578dbc0-bd0b-4845-8e6a-c89e6fab244f)

## Laporan Laba Rugi
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/78d93845-bdaa-4b79-848f-35a7907cfdf2)
## Laporan Posisi Keuangan
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/646e908d-ce3b-4d97-9b19-f23ba37e810b)
## Jurnal Penutup
![image](https://github.com/santaadelia/sistem-informasi-akuntansi/assets/152131711/adcadbef-bdca-4f68-9950-2419b3b18ab6)

