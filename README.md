## LAPORAN PRAKTIKUM 13
NAMA : ALI GUNAWAN | KELAS : TI.24.A3 | NIM : 312410400

## Tujuan Praktikum
Praktikum ini bertujuan untuk membangun aplikasi web sederhana berbasis PHP dengan konsep Object Oriented Programming (OOP) yang memiliki fitur autentikasi login, pengelolaan session, serta pembatasan akses halaman. Selain itu, praktikum ini melatih mahasiswa memahami penggunaan enkripsi password menggunakan password_hash() dan password_verify() agar sistem login lebih aman.

## Struktur Folder 
<img width="1919" height="1199" alt="struktur folder" src="https://github.com/user-attachments/assets/ea468813-e728-486a-abcc-6877267911a0" />

## Membuat Database Di Mysql
### Menambahkan user database
    CREATE DATABASE latihan_oop;
    USE latihan_oop;

### Membauat tabel baru user
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50),
    password VARCHAR(255),
    nama VARCHAR(100)
    );

### Menambahkan isi tabel user 
    ('admin', '$2y$10$uWdZ2x.hQfGqGz/..q7wue.3/a/e/e/e/e/e/e/e/e/e/e',
    'Administrator');

## LANGKAH - LANGKAH PRAKTIKUM

### Step 1
menambahkan code index.php
<img width="1202" height="1204" alt="code index" src="https://github.com/user-attachments/assets/9f193581-df5b-461b-87e4-bc7514c41ad1" />

### Step 2
menambahkan code config.php
<img width="850" height="482" alt="code config" src="https://github.com/user-attachments/assets/b1f242fb-deaf-4bfc-ac0f-bc0fa769aae1" />

### Step 3
menambahkan code class/database.php
<img width="956" height="1128" alt="code database" src="https://github.com/user-attachments/assets/2b8f222a-3631-4d66-bba3-a8a4f1382499" />

### Step 4
menambahkan code class/form.php
<img width="1542" height="900" alt="code form" src="https://github.com/user-attachments/assets/a206dc67-034f-4271-8bb8-d1dbc394b62e" />

### Step 5
menambahkan code module/artikel/index.php
<img width="2034" height="1964" alt="code index artikel" src="https://github.com/user-attachments/assets/b27b95c0-f5d2-4dca-87b4-3f6060759691" />

### Step 6
menambahkan code module/home/index.php
<img width="1220" height="406" alt="code index home" src="https://github.com/user-attachments/assets/ade0c983-3baa-448d-99fc-9da70b8d3367" />

### Step 7
menambahkan code module/user/login.php
<img width="1464" height="2078" alt="code login" src="https://github.com/user-attachments/assets/4ca7f38b-8601-4f51-b40a-c5c90e09babe" />

### Step 8
menambahkan code module/user/logout.php
<img width="1066" height="482" alt="code logout" src="https://github.com/user-attachments/assets/d2a8bfea-000f-4046-a0f3-67552c5dc805" />

### Step 9
menambahkan code module/user/profile.php
<img width="1542" height="1926" alt="code profile" src="https://github.com/user-attachments/assets/cc0ff5cd-b4c9-425b-b746-346413aee387" />

### Step 10
menambahkan code template/footer.php
<img width="428" height="444" alt="code footer" src="https://github.com/user-attachments/assets/59a61880-87f8-4844-8514-a6e5a4d0ea7b" />

### Step 11
menambahkan code template/header.php
<img width="1942" height="2116" alt="code header" src="https://github.com/user-attachments/assets/0d820d5d-9aeb-4a11-89dc-0d8e48ac3556" />

### Step 12
menambahkan code assets/css/style.css
<img width="1018" height="1394" alt="code css" src="https://github.com/user-attachments/assets/116c4d83-f983-4879-b31a-628023384312" />

## Hasil Tampilan
setelah menyelesaikan code php dan css, kita uji coba dengan masuk website "http://localhost/lab12_php_oop/"

### Tampilan Home
<img width="1919" height="1139" alt="tampilan home" src="https://github.com/user-attachments/assets/ee2c0038-f1aa-4f85-9043-bc106e258123" />

### Tampilan Login
setelah masuk ke tahap login masukann kode user 'admin' dan password 'admin123' setelah itu klik login
<img width="1919" height="1139" alt="tampilan login" src="https://github.com/user-attachments/assets/7126bca0-f6e8-412b-a771-8c3150a3714f" />

### Tampilan Header
<img width="1919" height="1138" alt="tampilan header" src="https://github.com/user-attachments/assets/6262d002-b4fe-47d2-a334-7ae787549e86" />

## Hasil Implementasi
Hasil akhir dari praktikum ini adalah aplikasi web yang dapat melakukan login dengan username dan password terenkripsi, membatasi akses halaman artikel hanya untuk user yang sudah login, serta menyediakan halaman profil untuk melihat data user dan mengubah password. Halaman artikel menampilkan data dummy sebagai representasi fitur CRUD yang dapat dikembangkan lebih lanjut.

## Kesimpulan
Berdasarkan hasil praktikum, dapat disimpulkan bahwa penerapan PHP OOP dengan session dan enkripsi password berhasil meningkatkan keamanan dan kerapihan struktur aplikasi. Sistem login dan pembatasan akses berjalan sesuai tujuan, sehingga aplikasi siap dikembangkan lebih lanjut dengan fitur CRUD yang lebih lengkap dan kompleks.







