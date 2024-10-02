# Lab1Web Praktikum
Nur Laila (312310149)
# Langkah-langkah pembuatan tab dasar
Buat file baru dengan nama lab1_tag_dasar.html       
Kemudian, buka file tersebut pada web browser  
![Cuplikan layar 2024-10-02 120303](https://github.com/user-attachments/assets/0724a4c0-bab6-4650-96ee-5ff0b3f4db71)
<!DOCTYPE html>
```sh
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tag HTML Dasar</title>
</head>
<body> 
```
# Langkah 1 : Membuat Paragraf
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>  
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>  

![Cuplikan layar 2024-10-02 062136](https://github.com/user-attachments/assets/3ec7b1b8-60e7-4f20-9f7d-c759278fd60b)

# Langkah 2: Membuat Judul
```sh
<h1>Belajar Dasar HTML</h1>
<h2>Paragraf pada HTML</h2>
```
h1 : untuk judul pertama  
h2 : untuk judul kedua  
![Cuplikan layar 2024-10-02 062412](https://github.com/user-attachments/assets/55b1f53d-f475-4c54-a361-be79fe469f4c)

# Langkah 3: Memformat Teks
```sh
<p>Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
```  
mark : untuk meng-highlight teks  
<b : untuk menebalkan (bold)  
<i : mengubah menjadi font italic  
<u : untuk menggaris bawahi  
![Cuplikan layar 2024-10-02 063015](https://github.com/user-attachments/assets/9bb9b578-f56d-4939-8e2e-d99674531872)


# Langkah 4 : Menyisipkan Gambar
```sh
   <h3>Menambahkan Gambar</h3>
    <img src="Logo-Universitas-Pelita-Bangsa.png" width="200" title="Logo Universitas Pelita Bangsa" alt="Logo Universitas Pelita Bangsa">
```
![Cuplikan layar 2024-10-02 063719](https://github.com/user-attachments/assets/52291d6f-b08f-4439-b7d3-cd1cd8d599b0)


# Langkah 5 : Menambahkan Hyperlink
```sh
    <nav>
        <a href="lab1_tag_dasar.html">Dasar HTML</a>
        <a href="halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
![Cuplikan layar 2024-10-02 065536](https://github.com/user-attachments/assets/eff5d107-aa3e-4c95-9b02-23fd8969cd07)

## JAWABAN DARI PERTANYAAN
## Nomor 1 :   
terjadi error ketika tidak sesuai dengan code yang seharusnya. contoh seperti dibawah ini :
![image](https://github.com/user-attachments/assets/f8f9b8d6-1489-458f-8fdb-f9a940db5d2b)  
contoh yang benarnya adalah  
```sh
<h1></h1>
```
bukan  
```sh
<h1></h2>
```
## Nomor 2 :   
Tag ``<p>`` digunakan untuk membuat paragraf dalam HTML, menampilkan teks sebagai blok dengan ruang di atas dan bawah. Sementara itu, tag ``<br>`` menambahkan baris baru tanpa membuat paragraf baru. Gunakan ``<br>`` untuk memisahkan teks dalam satu paragraf, dan ``<p>`` untuk memulai paragraf baru.

## Nomor 3 :   
Atribut `title` dalam tag `<img>` berfungsi untuk menyajikan informasi tambahan yang ditampilkan sebagai tooltip saat pengguna mengarahkan kursor ke gambar. Di sisi lain, atribut `alt` memberikan deskripsi teks alternatif yang berguna ketika gambar tidak dapat dimuat atau untuk mendukung pengguna dengan keterbatasan visual yang menggunakan pembaca layar. Selain itu, atribut `alt` memiliki peranan penting dalam SEO karena membantu mesin pencari dalam memahami isi gambar, sedangkan `title` bersifat opsional dan lebih ditujukan untuk meningkatkan pengalaman pengguna.

## Nomor 4 :   
Untuk menjaga proporsionalitas tampilan gambar, disarankan agar hanya satu dari dua atribut, yaitu `width` atau `height`, yang diisi, sedangkan yang lainnya dibiarkan kosong. Hal ini memungkinkan browser untuk secara otomatis menyesuaikan ukuran gambar sesuai dengan rasio aslinya. Pengisian kedua atribut dengan nilai yang tidak sesuai dapat menyebabkan distorsi pada gambar. Sebaliknya, jika kedua atribut diisi dengan nilai yang sesuai dengan rasio asli, gambar akan tetap terlihat proporsional.

## Nomor 5 :    
Atribut `target` pada elemen tautan (`<a>`) menentukan lokasi pembukaan halaman tujuan. Penggunaan nilai `_blank` akan membuka halaman di tab atau jendela baru. Sebaliknya, nilai `_self` akan membuka halaman di tab atau jendela yang sama, menggantikan konten yang ada (ini merupakan nilai default jika `target` tidak diatur). Nilai `_top` memungkinkan halaman terbuka di seluruh jendela, mengeluarkan dari semua frame atau iframe yang mungkin ada. Sementara itu, penggunaan `_parent` akan membuka halaman di frame induk, dan jika tidak ada frame induk, fungsinya sama dengan `_self`.
