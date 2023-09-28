# Praktikum 1

### Nama: Rini Ariza

### NIM: 312210337

### Kelas: TI.22.A3

---

### Praktikum
Pertama buat codingan sebagai berikut 
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

atur atribut paragraf
```
<p align="center">
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

![Screenshot (228)](https://github.com/rniarzz/Lab1Web/assets/115542704/bd79f905-f291-43a5-a293-04da759b4fe6)


### Menambahkan Judul 
```
<!-- paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

 <!-- paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```

![Screenshot (229)](https://github.com/rniarzz/Lab1Web/assets/115542704/3eb3b5f7-d669-43a3-adac-e7a93f075c25)


### Memformat Teks
```
<!-- paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<p>
  Kami sedang belajar HTML dasar, pada matakuliah <b>Pemograman Web</b> di
  prodi <i>Teknik Informatika</i> <mark>Universitas Pelita Bangsa</mark>.
  Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana
  dalam mengenal tag-tag dasar HTML.
</p>

<!-- paragraf kedua -->
<h2>Paragraf pada HTML</h2>
<p align="center">
  Ini adalah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga terbentuk menjadi kesatuan. Paragraf dengan menggunakan
  tag dasar HTML.
</p>
```

![Screenshot (229)](https://github.com/rniarzz/Lab1Web/assets/115542704/ee2f4865-2342-4c54-8b4a-0792df5af290)



### Menyisipkan Gambar
```
<h3>Menyisipkan gambar</h3>
<img src="Clarkson.jpg" width="480" />
```

![Screenshot (230)](https://github.com/rniarzz/Lab1Web/assets/115542704/b44072ac-fdf3-4d8e-ab01-0c1d8634edf6)


### Menambahkan Hyperlink
```
<nav>
<a href="lab1_tag_dasar.html"><b>DASAR HTML</b></a>
</nav>
```

![Screenshot (231)](https://github.com/rniarzz/Lab1Web/assets/115542704/ae4ecc5d-0766-4572-8dc3-191929b099a6)


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



