<h1 align="center">Selamat datang di Exbullience! 👋</h1>

[![](https://img.shields.io/github/issues/tsaqibfs/exbullience?style=flat-square)](https://img.shields.io/github/issues/tsaqibfs/exbullience?style=flat-square) ![](https://img.shields.io/github/stars/tsaqibfs/exbullience?style=flat-square)
![](https://img.shields.io/github/forks/tsaqibfs/exbullience?style=flat-square) ![](https://img.shields.io/github/license/tsaqibfs/exbullience?style=flat-square) [![saythanks](https://img.shields.io/badge/say-thanks-ff69b4.svg?style=flat-square)](https://saythanks.io/to/sokatsaqib%40gmail.com) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg?style=flat-square)](https://code.visualstudio.com/) [![GitHub followers](https://img.shields.io/github/followers/tsaqibfs.svg?style=flat-square&label=Follow&maxAge=2592000)](https://github.com/tsaqibfs?tab=followers)

<p align="center">
	
<img align="center" src="http://ForTheBadge.com/images/badges/built-with-love.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/uses-html.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/makes-people-smile.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/built-by-developers.svg">

</p>

### 🤔 Apa itu Exbullience?
Web Management Kelas yang dibuat oleh <a href="https://github.com/tsaqibfs"> Tsaqib Soka </a>. **Exbullience adalah Website untuk kelas agar para siswa dapat melihat jadwal pelajaran, jadwal piket, artikel, dan informasi lainnya melalui website dengan mudah.**

### 🤨 Fitur apa saja yang tersedia di Exbullience?
- Autentikasi Admin
- List Siswa & CRUD
- User & CRUD
- Jadwal piket & CRUD
- Jadwal Pelajaran & CRUD
- Settings (Dapat mengubah data website seperti judul, logo, favicon, dll)
- Artikel
- Dan lain-lain

### 📆 <a href="http://syauqi.js.org/">Release Date</a>
**Release date : 12 October 2022**
> Exbullience merupakan project open source yang dibuat oleh Tsaqib Soka. Kalian dapat download/fork/clone. Cukup beri stars di project ini agar memberiku semangat. Terima kasih!

------------

 ### 👤 Default Account for testing
	
**Admin Default Account**
- Username: admin
- Password: admin

------------

## 💻 Install

1. **Clone Repository**
```bash
git clone https://github.com/tsaqibfs/exbullience.git
cd exbullience
composer install
npm install
copy .env.example .env
```

2. **Buka ```.env``` lalu ubah baris berikut sesuai dengan databasemu yang ingin dipakai**
```
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

3. **Instalasi website**
```bash
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan storage:link
```

4. **Jalankan website**
```bash
php artisan serve
```

## 📝 License
- Copyright  © 2022 Tsaqib Soka.
- **Exbullience is open-sourced software licensed under the MIT license.**

------------

- **Made with ❤️ by Tsaqib Soka .**
- Thanks to <a href="http://devover.id">DevoverID</a>
- Exbullience is open-sourced software licensed under the MIT license.
