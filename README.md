# Lab9web

Nama : Muhammad Rifqi aziz

NIM  : 312210111

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode

2. Buat folder baru dengan nama `lab9_php_modular` pada docroot webserver (htdocs)

3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya

## Langkah-langkah Praktikum
- Jalankan Apache dan MySQL server dari menu XAMPP Control
- Kemudian buat folder baru dengan nama lab9_php_modular pada docroot webserver (c:\xampp\htdocs). Kemudian buka melalui browser dengan mengakses URL: http://localhost/lab9_php_modular/.

![1](https://github.com/syifaaurellia/Lab9web/assets/115867244/ab5f4256-e26d-47be-974b-67e51867e1aa)

1. Buat file dengan nama `header.php`
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
```

2. Buat file dengan nama `footer.php`
```
        <footer>
            <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

3. Buat file dengan nama `home.php`
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

4. Buat file dengan nama `about.php`
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

- Output halaman `Home` :
![2](https://github.com/syifaaurellia/Lab9web/assets/115867244/c1058bc0-3584-4a84-865d-046af8369cfc)


- Output halaman `About` :
![3](https://github.com/syifaaurellia/Lab9web/assets/115867244/51313ca1-49ee-4552-914e-6e2abc1ce828)


## Pertanyaan dan Tugas
> Implementasikan konsep modularisasi pada kode program Praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

1. Buat folder baru dengan nama `lab9_php_praktikum`
![4](https://github.com/syifaaurellia/Lab9web/assets/115867244/f79373d0-08c9-4b93-9d46-7e7d11ac8e0a)

- Setelah itu buat beberapa file sama seperti file-file yang ada pada praktikum 8, untuk script lebih lengkapnya kalian dapat langsung lihat pada folder [lab9_php_praktikum](https://github.com/syifaaurellia/Lab9web/tree/main/lab9_php_praktikum).

2. Hasil Output `koneksi.php` :
![1](https://github.com/iki020904/Lab9web/assets/115804283/4063e471-5fdf-4765-966a-389daa11a3a2)


3. Hasil Output `home.php` :
   ![2](https://github.com/iki020904/Lab9web/assets/115804283/d5c84030-71f7-4ec8-8490-5ca247edf215)



5. Hasil Output `tambah.php` :
![3](https://github.com/iki020904/Lab9web/assets/115804283/03058a08-9873-474d-b770-ec95e0d6a320)


![4](https://github.com/iki020904/Lab9web/assets/115804283/ddfbc8e8-981b-41bb-8ad3-295a2a624980)


![5](https://github.com/iki020904/Lab9web/assets/115804283/c0ae3939-dd5e-4027-a60e-f422ce2ef6ff)



5. Hasil Output `ubah.php` :
![6](https://github.com/iki020904/Lab9web/assets/115804283/29912ae5-0cc6-4b40-af67-a9a38f6adabb)

![7](https://github.com/iki020904/Lab9web/assets/115804283/146e77e6-5f3b-46c2-a220-7df578552339)


6. Hasil Output `hapus.php` :
![8](https://github.com/iki020904/Lab9web/assets/115804283/6727990b-35cf-4463-bfec-57b89f80d2b2)



## Finish, Terima Kasih
