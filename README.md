# PBO-Abstraction-Encapsulation-Inheritance-Polymorphism
# Latihan PBO: Bentuk, BujurSangkar, Lingkaran, dan Silinder

## Deskripsi
Program ini dibuat untuk menyelesaikan Exercise 1, Exercise 2, dan Exercise 3 pada materi Pemrograman Berorientasi Objek (PBO) menggunakan bahasa Java.

Program ini menghitung luas bujur sangkar, luas lingkaran, dan volume silinder.

## Daftar File
- `Bentuk.java`
- `BujurSangkar.java`
- `Lingkaran.java`
- `Silinder.java`
- `Main.java`

## Konsep OOP

### 1. Encapsulation
Encapsulation diterapkan dengan menggunakan atribut `private` dan method getter serta setter untuk mengakses atau mengubah nilai atribut.

Contohnya terdapat pada atribut `warna`, `sisi`, `radius`, dan `tinggi`.

### 2. Inheritance
Inheritance diterapkan menggunakan kata kunci `extends`.

- `BujurSangkar` mewarisi class `Bentuk`.
- `Lingkaran` mewarisi class `Bentuk`.
- `Silinder` mewarisi class `Lingkaran`.

### 3. Polymorphism
Polymorphism diterapkan menggunakan method overriding pada method `printInfo()`. Setiap class menampilkan informasi yang berbeda sesuai dengan objeknya.

## Cara Menjalankan Program
1. Buka folder program di Visual Studio Code.
2. Buka terminal pada folder tersebut.
3. Compile program menggunakan perintah:

   `javac *.java`

4. Jalankan program menggunakan perintah:

   `java Main`

## Screenshot Hasil Program

Berikut adalah hasil output program Java:

![Hasil Program](hasil.png)
