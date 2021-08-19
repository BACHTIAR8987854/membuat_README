# Perpustakaan

**Version 1.0.0** - [ChangeLog SourceCode](https://github.com/BACHTIAR8987854)

Website sistem informasi perpustakaan yang dibuat dengan bahasa PHP. Aplikasi Perpustakaan ini dibuat untuk mempermudah pencatatan peminjaman buku, sehingga mengurangi kemungkinan kesalahan rekap data. Project ini merupakan project sederhana dari aplikasi perpustakaan sebenarnya.

## Petunjuk Instalasi

Software yang diperlukan :
1. [XAMPP dan sejenisnya](https://www.apachefriends.org/download.html)
2. [Composer](https://getcomposer.org/)

### Hal yang perlu di install :

 ```html
1. PHP >= 7.0.0
2. OpenSSL PHP Extension
3. PDO PHP Extension
4. Mbstring PHP Extension
5. Tokenizer PHP Extension
6. XML PHP Extension
 ```
 Anda bisa baca selengkapnya disini [Laravel 8.x Server requirements](https://laravel.com/docs/8.x)
 
 ## Petunjuk Konfigurasi
 
 ```html
1. Clone repository ke local direktori anda.
2. Masuk ke direktori penginstallan.
3. Buka terminal / cmd ketik "composer install" dan tekan enter untuk menginstall dependency php.
4. Ketik "npm install" untuk menginstall package javascript.
5. Rename ".env.example" menjadi ".env".
6. Setting file .env sesuai databse anda.
7. Jalankan perintah "php artisan:key generate" dan "php artisan jwt:key" di terminal /cmd.
 ```
 
  ## Penjelasan Struktur/Hirarki Program
  
  ![68747470733a2f2f696d6167652e6962622e636f2f64455a6462562f6572642d70657270757374616b61616e2e706e67](https://user-images.githubusercontent.com/60456760/130034839-ed324d57-e43d-4b5f-b6e4-4dd0705524cb.png)
  
  1. sudah harus terdaftar sebagai anggota perpustakaan
  2. adapun syarat menjadi anggota harus sudah memiliki :
     a. nama
     b. id
     c. username
     d. password
     e. alamat
     f. status
  3. input tanggal meminjam dan tanggal mengembalikan.
  4. meminjam buku yang sudah ada syarat atau data yaitu:
     a. pengarang
     b. judul
     c. id
     d. penerbit
     e. tahun
     f. kategori
  5. mengembalikan sesuai dengan taggal yang sudah diinput di perintah nomer 3.

  ## License & copyright
  
  project ini dilindungi hak cipta atas kekayaan intelektual  Copyright &copy; 2021. All Right Reserved - see the [LICENSE.md](https://github.com/BACHTIAR8987854) file for details
  
  ## Change log
  
  ### v1.0.0 - 19 Agustus 2021
  
  initial release.
  
  **Added:**
  - Readme
  - Change log
  - License & copyright
  
  
  
  
  
  


