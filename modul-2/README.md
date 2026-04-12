# Modul 2
<h1 align="center">LAPORAN PRAKTIKUM</h1>
<h1 align="center">APLIKASI BERBASIS PLATFORM</h1>

<br>

<h2 align="center">MODUL 2</h2>
<h2 align="center">HTML</h2>

<br><br>

<p align="center">
<img src="logo.png" width="350">
</p>
<br><br><br>

<h2 align="center">Disusun Oleh :</h2>

<p align="center" style="font-size:28px;">
  <b>Imelda Fajar</b><br>
  <b>2311102004</b><br>
  <b>S1 IF</b>
</p>
<br>
<h2 align="center">Dosen Pengampu :</h2>

<p align="center" style="font-size:28px;">
  <b>Dimas Fanny Hebrasianto Permadi, S.ST., M.Kom</b>
</p>
<br>
<h2 align="center">Asisten Praktikum :</h2>

<p align="center" style="font-size:28px;">
  <b>Apri Pandu Wicaksono</b><br>
  <b>Rangga Pradarrell Fathi</b>
</p>
<br>
<h1 align="center">LABORATORIUM HIGH PERFORMANCE</h1>
<h1 align="center">FAKULTAS INFORMATIKA</h1>
<h1 align="center">UNIVERSITAS TELKOM PURWOKERTO</h1>
<h1 align="center">TAHUN 2026</h1>

<hr>

### Dasar Teori
HTML (HyperText Markup Language) adalah bahasa markup yang digunakan untuk menyusun dan menampilkan struktur dasar halaman web. Dengan HTML, berbagai elemen seperti teks, gambar, link, dan tabel dapat ditampilkan secara terstruktur di browser. HTML bekerja menggunakan tag-tag tertentu yang memiliki fungsi masing-masing dalam membentuk suatu tampilan halaman.

Salah satu elemen yang sering digunakan dalam HTML adalah tabel. Tabel berfungsi untuk menyajikan data dalam bentuk baris dan kolom agar lebih mudah dibaca dan dipahami. Pembuatan tabel dilakukan dengan beberapa tag utama seperti <table> sebagai wadah, <tr> untuk baris, <th> untuk judul kolom, dan <td> untuk isi data. Dengan kombinasi tag tersebut, data dapat ditampilkan secara rapi dan terorganisir.

Selain itu, dalam pembuatan tampilan sederhana tanpa CSS, HTML juga menyediakan beberapa tag tambahan seperti <center> untuk mengatur posisi ke tengah dan <br> untuk memberi jarak antar elemen. Meskipun cara ini tergolong sederhana, namun cukup efektif untuk memahami dasar pembuatan tampilan web.

---

### Source Code
```html
<!DOCTYPE html>
<html>
<head>
<title>Tugas 2 - Tabel Dasar</title>
</head>

<body>

<br><br><br><br><br><br><br><br>

<center>
<table border="1" cellspacing="0">
<tr>
<th>Nama Lengkap</th>
<th>Kota Kelahiran</th>
<th>Age</th>
</tr>

<tr>
<td>Imelda</td>
<td>Pati</td>
<td>20</td>
</tr>

<tr>
<td>Fajar</td>
<td>Purwokerto</td>
<td>21</td>
</tr>

<tr>
<td>Crisyanti</td>
<td>Semarang</td>
<td>28</td>
</tr>

</table>
</center>

</body>
</html>

### Output 
Program menghasilkan tampilan tabel sederhana yang berada di tengah halaman. Tabel memiliki 3 kolom yaitu Nama Lengkap, Kota Kelahiran, dan Age, serta berisi 3 data yang telah dimasukkan, yaitu Imelda, Fajar, dan Crisyanti.

<img src="output.png">

---

### Pembahasan Source Code
Pada program ini, tabel ditampilkan di tengah halaman tanpa menggunakan CSS. Untuk mengatur posisi tabel secara horizontal digunakan tag `<center>`, sedangkan untuk memberi jarak ke bawah digunakan beberapa tag `<br>` agar tabel terlihat berada di bagian tengah halaman.

Tag `<!DOCTYPE html>` digunakan sebagai deklarasi bahwa dokumen menggunakan HTML5. Tag `<html>` merupakan pembungkus seluruh isi halaman. Bagian `<head>` berisi informasi tambahan seperti judul halaman yang ditampilkan melalui tag `<title>`.

Tag `<body>` berisi seluruh elemen yang akan ditampilkan pada browser. Untuk membuat tabel digunakan tag `<table>` dengan atribut `border="1"` agar garis tabel terlihat dan `cellspacing="0"` agar jarak antar sel tidak renggang.

Tag `<tr>` digunakan untuk membuat baris pada tabel. Tag `<th>` digunakan sebagai judul kolom, yaitu Nama Lengkap, Kota Kelahiran, dan Age. Sedangkan tag `<td>` digunakan untuk mengisi data pada setiap baris tabel.

Data yang ditampilkan pada tabel ini terdiri dari:
- Imelda, Pati, 20  
- Fajar, Purwokerto, 21  
- Crisyanti, Semarang, 28  

Secara keseluruhan, program ini menampilkan tabel sederhana yang berisi data identitas dan diletakkan di tengah halaman tanpa menggunakan CSS.

---

### Kesimpulan
Berdasarkan hasil program yang dibuat, HTML dapat digunakan untuk menampilkan tabel sederhana dengan mudah menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>`. Selain itu, posisi tabel dapat diatur di tengah halaman tanpa CSS dengan memanfaatkan tag `<center>` dan `<br>`. Program ini telah sesuai dengan tujuan, yaitu menampilkan tabel dasar secara sederhana dan terstruktur.
