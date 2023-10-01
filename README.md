<h1 <p align="center"><b>Praktikum 1</b></p></h1> 

**Nama: Rini Ariza**

**NIM: 312210337**

**Kelas: TI.22.A3**

---

## Membuat Paragraf
Pertama buat codingan untuk membuat sebuah paragraf

Untuk membuat sebuah paragraf gunakan perintah `<p>` dan diakhiri dengan `</p>` 

berikut syntaxnya:

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

![IMG-20231001-WA0014](https://github.com/rniarzz/Lab1Web/assets/115542704/38c66321-baa5-4e99-8ba0-dcff47094979)

---

## Mengatur Atribut Paragraf

Untuk mengatur atribut paragraf kita bisa menggunakan perintah-perintah sebagai berikut:

- Mengatur paragraf **rata kanan** gunakan perintah `align="right"`
- Mengatur paragraf **rata kiri** gunakan perintah `align="left"`
- Mengatur paragraf **rata tengah** gunakan perintah `align="center"`
- Mengatur paragraf **rata kanan-kiri** gunakan perintah `align="justify"`

Berikut contoh syntax untuk mengatur paragraf menjadi rata tengah:

```html
<p align="center">
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

Kemudian simpan perubahannya lalu masuk web browser dan refresh lagi, berikut hasilnya

![IMG-20231001-WA0007](https://github.com/rniarzz/Lab1Web/assets/115542704/4b937f74-f37e-4c03-b902-712949663b54)


---

## Menambahkan Judul 

Untuk menambahkan judul kita bisa menggunakan format mulai dari heading 1 sampai heading 6

Format `<h1>` untuk menambahkan judul, format `<h2>` sampai `<h6>` untuk sub judul

Berikut contoh syntax penggunaan `<h1>` dan `<h2>`:

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

Kemudian simpan perubahannya lalu masuk web browser dan refresh lagi, berikut hasilnya

![IMG-20231001-WA0010](https://github.com/rniarzz/Lab1Web/assets/115542704/5b64ca0e-20cd-4f1c-9aa4-aaf84ed32841)


---

## Memformat Teks

Untuk menambahkan format teks disini saya menggunakan beberapa perintah sebagai berikut:
- `<mark>` = Untuk menandai teks
- `<b>` = Untuk menebalkan teks
- `<i>` = Untuk memiringkan teks
- `<u>` = Untuk menggaris bawahi teks

Berikut syntaxnya:

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

Kemudian simpan perubahannya lalu masuk web browser dan refresh lagi, berikut hasilnya

![IMG-20231001-WA0009](https://github.com/rniarzz/Lab1Web/assets/115542704/98e9d766-1ea7-41dd-b591-df84d499bf3e)

---

## Menyisipkan Gambar

Untuk menyisipkan gambar, HTML menyediakan tag khusus untuk dapat menampilkan gambar. Tag yang digunakan untuk menampilkan gambar adalah `<img>` dengan atribut `src` sebagai URL atau Path file gambar berada. Tag ini dapat memuat gambar dengan berbagai jenis ekstensi file gambar.

Adapun atribut lain yang dapat digunakan untuk pengaturan gambar sebagai berikut:

![IMG_20230930_133448](https://github.com/rniarzz/Lab1Web/assets/115542704/e529b11b-c861-4613-9e05-71b524273b43)


Berikut contoh syntaxnya:

```html 
<h3>menambahkan gambar HTML</h3>
<img src="http://www.pelitabangsa.ac.id/wp-content/uploads/2019/09/LOGO_UPB_NEW-1.png" width="300">

```

Kemudian simpan perubahannya lalu masuk web browser dan refresh lagi, berikut hasilnya

![IMG-20231001-WA0008](https://github.com/rniarzz/Lab1Web/assets/115542704/4c0060b3-d3f4-4de9-bc12-be464475ba68)

---

## Menambahkan Hyperlink

Untuk membuat Hyperlink atau Anchor kita bisa menggunakan tag `<a>` dengan menambahkan atribut `href` 
sebagai penentu URL yang dimaksud.

Berikut contoh syntaxnya:

```html
<nav>
    <a href="lab1_tag_dasar.html">DASAR HTML Rini Ariza</a>
</nav>
```

Kemudian simpan perubahannya lalu masuk web browser dan refresh lagi, berikut hasilnya (ada di bagian paling atas halaman web)

![IMG-20231001-WA0011](https://github.com/rniarzz/Lab1Web/assets/115542704/c3ac1a53-ebb5-4e27-8ca0-32ad877e81c9)

---

## Menjawab Pertanyaan

<b>1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag? </br>
Jawab: </b> </br>
Tidak ada error dan HTML akan berjalan seperti normal. 

<b>2. Apa perbedaan dari tag `< p >` dengan tag `< br >` , berikan penjelasannya! <br>
Jawab: </b>
- ```<br>``` digunakan untuk memindahkan teks ke baris selanjutnya
- ```<p>``` digunakan untuk membuat paragraf baru, membuat teks berada dalam sebuah paragraf  

<b>3. Apa perbedaan atribut ```title``` dan ```alt``` pada tag ```<img>```, berikan penjelasannya! <br>
Jawab: </b>
- ```alt``` digunakan untuk menentukan teks alternatif untuk suatu gambar, jika gambar tidak dapat ditampilkan.
- ```title``` digunakan untuk memberikan keterangan tambahan pada elemen. Text yang dimasukkan pada atribut title ini akan terlihat ketika kursor diletakkan diatas elemen yang bersangkutan.

<b>4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! <br>
Jawab: </b> </br>
Hanya dengan menggunakan ```width``` foto akan menjadi lebih presisi, tetapi ```height``` bisa mengatur foto semaunya 

<b>5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( ```_blank```, ```_self```, ```_top```, ```_parent``` ), apa yang terjadi pada masing-masing nilai atribut tersebut? <br>
Jawab: </b> 
- ```_blank```: Membuka dokumen yang dituju di jendela atau tab baru. 
- ```_self```: Membuka dokumen yang dituju di jendela atau frame yang sama dengan elemen yang diklik. Ini adalah nilai default jika atribut target tidak ditentukan. 
- ```_parent```: Membuka dokumen yang dituju di frame <i>parent</i> dari elemen yang diklik. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self. 
- ```_top```: Membuka dokumen yang dituju di jendela penuh, menggantikan semua frame, termasuk frame luar. Jika elemen tersebut tidak ada dalam frame, perilakunya sama seperti _self. 

<h1 <p align="center"><b>======== Sekian Terima Kasih ==========</b></p></h1>
