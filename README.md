# Test PT. Jagat Teknologi Indonesia

A. Kebutuhan
  1. XAMPP      -> https://www.apachefriends.org/
  2. Composer   -> https://getcomposer.org/
  3. NodeJs     -> https://nodejs.org/

B. Konfigurasi
  1. Database\
    a. Download "database.sql"\
    b. Buat database dengan nama "mysql-27"\
    c. Import "database.sql" ke "mysql-27"
  2. Backend\
    a. Download dan Extract "backend.zip"\
    b. Masuk ke Root Folder\
    c. Buka di terminal\
    d. Jalankan "composer install"\
    e. Jalankan "php artisan serve"\
    f. Buka URL "localhost:8000/firebase/view" di Browser
  3. Front End\
    a. Download dan Extract "frontend.zip"\
    b. Masuk ke Root Folder\
    c. Buka di terminal\
    d. Jalankan "npm install"\
    e. Jalankan "npm run serve"\
    f. Buka URL "localhost:8080/login" di Browser
    
C. Teknologi
  1. MySql
  2. Laravel    -> https://laravel.com/
  3. Vue CLI 3  -> https://cli.vuejs.org/
  4. Firebase   -> https://firebase.google.com/
  5. Bootstrap  -> https://getbootstrap.com/
    
D. Catatan
  1. URL "localhost:8000/firebase/view" terhubung realtime dengan "localhost:8080/number"
  2. Tetap hidupkan server untuk "database", "backend" dan "frontend" secara bersamaan
  3. Penamaan database harus "mysql-27" dengan username "root" dan tanpa password
  4. Konfigurasi database dapat dilakukan di file ".env" dapa "Root Folder Backend"
