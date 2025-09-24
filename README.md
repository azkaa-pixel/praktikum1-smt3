# praktikum1 - smt3

## modul praktikum pemrograman web 

nama : ghefira azka fardani 

nim : 312410521

kelas : TI.24.A5

### menamakan file 
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%201.png) 

#### ```hasil``` 
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%202.png) 

### 1. membuat paragraf 
```html
<!-- Ini adalah paragraf pertama --> 
<p>
Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa.
Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
</p> 
<!-- Ini adalah paragraf kedua --> 
<p>
Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan.
Paragraf dibuat dengan menggunakan tag dasar html.
</p>
```
#### ```- hasil```
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%203.png) 

#### ```- penjelasan``` :
Tag ```<p>``` digunakan untuk membuat paragraf. Setiap kali kamu menulis ```<p>``` ... ```</p>```, browser otomatis memberi jarak antar paragraf.

### kemudian mengatur atribut berikut dan amati perubahan nya 

```html
<!-- Ini adalah paragraf pertama --> 
<p style="text-align: center;">
Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa.
Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
</p> 
<!-- Ini adalah paragraf kedua --> 
```<p style="text-align: right;">```
Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan.
Paragraf dibuat dengan menggunakan tag dasar html.
</p>
```
#### ```- hasil```
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%204.png) 

#### ```- penjelasan``` :
Tag ```<p style="text-align: center;">``` digunakan untuk membuat paragraf dengan gaya CSS yang mengatur teks agar tampil rata tengah secara horizontal di halaman web.



### 2. menambahkan judul 
```html
<!-- judul paragraf pertama --> 
<h1>Belajar Dasar HTML</h1> 
 
<!-- judul paragraf kedua --> 
<h2>Paragraf pada HTML</h2> 
```
#### ```- hasil``` 
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%205.png) 

#### ```- penjelasan``` :
Tag ```<h1>``` sampai ```<h6>``` digunakan untuk heading (judul). ```<h1>``` adalah judul terbesar, sedangkan ```<h6>``` adalah yang terkecil.


### 3. memformatkan teks 

```html
<mark>HTML dasar</mark>
```
#### ```- hasil```
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%205.png) 

#### ```- penjelasan``` :
Tag HTML bisa dipakai untuk menambahkan format ke teks. Contohnya ```<b>``` untuk bold, ```<i>``` untuk italic, ```<mark>``` untuk highlight, ```<sub>``` untuk subscript, dan ```<sup>``` untuk superscript.


### 4. menyisipkan gambar 
#### membuat 
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%206.png) 

``` html
<!-- sub judul paragraf --> 
<h3>Menambahkan Gambar</h3> 
 
<!-- menambahkan gambar pada dokumen --> 
<img src="Logo_UPB.jpeg" title="Logo Univeritas Pelita Bangsa">
```
#### ```- hasil``` 
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%207.png) 

#### ```- penjelasan``` :
Tag ```<img>``` digunakan untuk menampilkan gambar.

- src menunjuk lokasi gambar.
  
- width dan height untuk mengatur ukuran.
  
- title untuk memberi keterangan gambar (muncul saat mouse diarahkan).

#### mengatur ukuran foto
``` html
<!-- menambahkan gambar pada dokumen --> 
<img src="Logo_UPB.jpeg" width="200" title="Logo Univeritas Pelita Bangsa">
```

### ```- hasil```
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%208.png) 

#### ```- penjelasan``` :
Kode kedua menampilkan gambar yang sama tetapi lebarnya diatur menjadi 200 piksel sehingga tampil lebih kecil dan proporsiona

### 5. menambahkan hyperlink
menambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut :
```html
<!-- menambahkan link navigasi --> 
<nav> 
<a href="lab1_tag_dasar.html">Dasar HTML</a> 
<a href="lab1_halaman2.html">Halaman 2</a> 
<a href="http://www.google.com">Halaman Web Eksternal Google</a> 
</nav> 
<hr>
```

####  ```- hasil``` 
![foto](https://github.com/azkaa-pixel/praktikum1-smt3/blob/08e33fc59ff048087300dc22934bb60964d2ea3e/ss%20praktikum%201%20-%20se3/ss%209.png) 

#### ```- penjelasan``` :
Tag ```<a>``` membuat hyperlink. Atribut ```href``` berisi alamat tujuan. Link bisa menuju file lokal (halaman lain di proyek) atau website eksternal.


## menjawab pertanyaan 
1.	Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
    
2.	Apa perbedaan dari tag ```<p>``` dengan tag ```<br>``` , berikan penjelasannya! 
   
3.	Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
   
4.	Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut
   diisi semua atau tidak? Berikan penjelasannya!
  	
5.	Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada
    masing-masing nilai antribut tersebut?
   
### jawaban 
1. ada,saat kesalahan penulisan tag, maka hasil di browser bisa tidak sesuai, ada error di tampilannya , atau kode tidak terbaca dengan benar.

2. Tag ```<p>``` membuat paragraf baru lengkap dengan jarak atas-bawah, kalau ```<br>``` hanya memindahkan teks ke baris baru tanpa membuat paragraf.

3. Atribut ```title``` : menampilkan keterangan saat kursor diarahkan ke gambar
   ```alt``` : menampilkan teks pengganti jika gambar tidak bisa dimuat.

5. Sebaiknya cukup isi salah satu, misalnya ```width```, supaya tinggi menyesuaikan otomatis; jika keduanya diisi sembarangan, gambar bisa terlihat tidak proporsional.

6. ```blank``` → membuka link di tab baru,

   ```self``` → membuka di tab/halaman yang sama,

   ```top``` → membuka di jendela paling atas (keluar dari frame),

   ```parent``` → membuka di frame induk jika ada.
















 	 

