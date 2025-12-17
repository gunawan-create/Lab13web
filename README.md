## LAPORAN PRAKTIKUM 13
NAMA : ALI GUNAWAN | KELAS : TI.24.A3 | NIM : 312410400

## Tujuan Praktikum
Praktikum ini bertujuan untuk membangun aplikasi web sederhana berbasis PHP dengan konsep Object Oriented Programming (OOP) yang memiliki fitur autentikasi login, pengelolaan session, serta pembatasan akses halaman. Selain itu, praktikum ini melatih mahasiswa memahami penggunaan enkripsi password menggunakan password_hash() dan password_verify() agar sistem login lebih aman.

## Struktur Folder 

## DATABASE (phpMyAdmin)
### CREATE DATABASE latihan_oop;
### USE latihan_oop;

### CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50),
    password VARCHAR(255),
    nama VARCHAR(100)
);

### INSERT INTO users (username, password, nama) VALUES
('admin', '$2y$10$uWdZ2x.hQfGqGz/..q7wue.3/a/e/e/e/e/e/e/e/e/e/e', 'Administrator');


## LANGKAH - LANGKAH PRAKTIKUM

### Step 1
menambahkan code 

