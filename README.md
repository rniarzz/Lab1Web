<h2 <p align="center"><b>Praktikum 1</b></p> </h2> 

**Nama: Rini Ariza**   

**NIM: 312210337**

**Kelas: TI.22.A3**

---

## Praktikum
Pertama buat codingan sebagai berikut untuk membuat sebuah paragraf

```html
<!-- ini adalah paragraf pertama -->
<p>
  Kami sedang belajar HTML dasar, pada matakuliah Pemograman Web di
  prodi Teknik Informatika Universitas Pelita Bangsa
  Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
  dalam mengenal tag-tag dasar HTML.
</p>

<!-- ini adalah paragraf kedua -->
<p>
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

Kemudian simpan perubahannya dan buka web browser kemudian refresh, berikut hasilnya

![Screenshot (226)](https://github.com/rniarzz/Lab1Web/assets/115542704/67b90ab3-0347-4fa3-8b64-cb48e18397f1)

---

## Mengatur atribut paragraf

Untuk mengatur atribut paragraf kita bisa menggunakan perintah-perintah sebagai berikut:

- 

```html
<p align="center">
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

![Screenshot (228)](https://github.com/rniarzz/Lab1Web/assets/115542704/bd79f905-f291-43a5-a293-04da759b4fe6)


### Menambahkan Judul 

```html
 <!-- Judul paragraf pertama -->
 <h1>Belajar Dasar HTML</h1>
 <p align="center">
     Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
     Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
     adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
     HTML.
 </p>

<!-- Judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
    <!-- Ini adalah paragraf kedua -->
<p align="left">
    Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>

```

![image](https://github.com/rniarzz/Lab1Web/assets/115542704/aaa22846-e963-449f-ab5a-ebbccc9754a1)


### Memformat Teks

```html
 <!-- Judul paragraf pertama -->
 <h1>Belajar Dasar HTML</h1>
 <p align="center">
     Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi
     <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat
     adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
     HTML.
 </p>

<!-- Judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
    <!-- Ini adalah paragraf kedua -->
<p align="left">
    Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>

```

![Screenshot (232)](https://github.com/rniarzz/Lab1Web/assets/115542704/bde22741-18c6-4c34-a0b9-da38f3bae312)

### Menyisipkan Gambar
```
<h3>menambahkan gambar HTML</h3>
<img src="http://www.pelitabangsa.ac.id/wp-content/uploads/2019/09/LOGO_UPB_NEW-1.png" width="300">

```

![Screenshot (230)](https://github.com/rniarzz/Lab1Web/assets/115542704/b44072ac-fdf3-4d8e-ab01-0c1d8634edf6)


### Menambahkan Hyperlink
```
<nav>
    <a href="lab1_tag_dasar.html">DASAR HTML Rini Ariza</a>
</nav>
```

![image](https://github.com/rniarzz/Lab1Web/assets/115542704/e7204d60-af29-44fb-90b7-fa4a102116d6)


#### Menjawab Pertanyaan

<b>1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
error ketika terjadi kesalahan penulisan tag? </b> <br>
Tidak ada error dan HTML akan berjalan seperti normal. 
<br>

<b>2. Apa perbedaan dari tag ```< p >``` dengan tag ```< br >``` , berikan penjelasannya! </b> <br>
```<br>``` digunakan untuk menggerakan teks ke barisan baru sedangkan ```<p>``` digunakan untuk membuat paragraf baru, ```<br>``` bisa digunakan untuk menambah barisan baru kedalam sebuah teks.
<br>

<b>3. Apa perbedaan atribut ```title``` dan ```alt``` pada tag ```<img>```, berikan penjelasannya! </b> <br>
```alt``` adalah untuk menyediakan tag alt gambar untuk menggambarkan gambar ke crawler mesin pencari dan pembaca layar untuk aksesibilitas web yang lebih baik. ```title``` adalah untuk memberikan penjelasan tentang tag alt gambar dan URL gambar dalam atribut ```src```.
<br>

<b>4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! </b> <br>
Hanya dengan menggunakan ```width``` foto akan menjadi lebih presisi tetapi ```height``` bisa mengatur foto semaunya 
<br>

<b>5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( ```_blank```, ```_self```, ```_top```, ```_parent``` ), apa yang terjadi pada masing-masing nilai antribut tersebut? </b> <br>
- ```_blank```: Membuka dokumen yang dituju di jendela atau tab baru. 
- ```_self```: Membuka dokumen yang dituju di jendela atau frame yang sama dengan elemen yang diklik. Ini adalah nilai default jika atribut target tidak ditentukan. 
- ```_parent```: Membuka dokumen yang dituju di frame <i>parent</i> dari elemen yang diklik. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self. 
- ```_top```: Membuka dokumen yang dituju di jendela penuh, menggantikan semua frame, termasuk frame luar. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self. 



