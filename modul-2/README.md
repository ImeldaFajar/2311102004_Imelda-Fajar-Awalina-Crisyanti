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
HTML (HyperText Markup Language) merupakan bahasa dasar yang digunakan untuk menyusun struktur halaman web. Dengan HTML, berbagai elemen seperti teks, gambar, dan tabel dapat ditampilkan secara terstruktur di browser.

Tabel dalam HTML digunakan untuk menyajikan data dalam bentuk baris dan kolom agar lebih mudah dibaca. Pembuatan tabel menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>`. Selain itu, tag `<center>` dan `<br>` dapat digunakan untuk mengatur posisi dan jarak tampilan tanpa menggunakan CSS.

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
...

### Output

Program menghasilkan tabel sederhana yang berada di tengah halaman dengan 3 kolom, yaitu Nama Lengkap, Kota Kelahiran, dan Age. Data yang ditampilkan adalah Imelda, Fajar, dan Crisyanti.

<img src="output.png">

---

### Pembahasan Source Code

Pada program ini, tabel ditampilkan di tengah halaman tanpa menggunakan CSS. Posisi diatur menggunakan tag `<center>`, sedangkan jarak ke bawah menggunakan beberapa tag `<br>`.

Tag `<!DOCTYPE html>` menunjukkan bahwa dokumen menggunakan HTML5. Tag `<html>` adalah pembungkus seluruh isi halaman. Bagian `<head>` berisi judul halaman melalui `<title>`, sedangkan `<body>` berisi seluruh tampilan.

Tabel dibuat dengan `<table>` menggunakan atribut `border="1"` untuk garis dan `cellspacing="0"` agar tidak ada jarak antar sel. Baris dibuat dengan `<tr>`, judul kolom dengan `<th>`, dan isi data dengan `<td>`.

Data yang ditampilkan:
- Imelda, Pati, 20  
- Fajar, Purwokerto, 21  
- Crisyanti, Semarang, 28  

---

### Kesimpulan

HTML dapat digunakan untuk membuat tabel sederhana dengan mudah menggunakan tag `<table>`, `<tr>`, `<th>`, dan `<td>`. Tampilan dapat diatur di tengah halaman tanpa CSS dengan bantuan `<center>` dan `<br>`. Program ini berhasil menampilkan data secara rapi dan terstruktur.
