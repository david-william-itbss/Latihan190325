<!DOCTYPE html>
<html>
    <head>
    <style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
  
}
</style>
</head>
<body>

    
        <h1>Selamat Datang</h1>
        <P>Belajar elemen semantik HTML</P>
    
<nav>
    <a href="#tentang.html">Tentang</a> |
    <a href="#kursus.html">Kursus</a> |
    <a href="#kontak">Kontak</a> |
</nav>
<h2>Tentang halaman ini</h2>
<p>ini merupakan halaman tentang website ini</p>

<h2>Pilihan Kursus</h2>

<table style="width:23%">
  <tr>
    <th>No</th>
    <th>Nama Kursus</th>
    <th>Durasi</th>
  </tr>
    <tr>
        <th>1</th>
        <th>Dasar HTML dan CSS</th>
        <th>4 minggu</th>
    </tr>
    <tr>
        <th>2</th>
        <th>Javascript</th>
        <th>6 minggu</th>
    </tr>
</table>

<h2>Hubungi kami</h2>
      <form action="/action_page.php">
    <label for="name">Nama:</label><br>
    <input type="text" id="name" name="name" value=" "><br>
    <br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" value=" "><br>
    <br>
    <label for="message">Pesan:</label><br>
    <textarea id="message" name="message" rows="10" cols="20"></textarea><br>
    <input type="submit" value="Submit">
  </form>
  <br>

  <h2>Pendaftaran Kampus ITBSS</h2>
      <form action="/action_page.php">
    <label for="name1">Masukkan nama anda</label><br>
    <input type="text" id="name1" name="name1" value=" "><br>
    <br>
    <label for="date1">Masukkan tanggal lahir anda</label><br>
    <input type="date" id="date1" name="date1"><br>
    <br>
    <label>Masukkan jenis kelamin anda</label><br>
    <input type="radio" id="laki-laki" name="gender1" value="Laki-laki">
    <label for="laki-laki">Laki-laki</label><br>
    <input type="radio" id="perempuan" name="gender1" value="Perempuan">
    <label for="perempuan">Perempuan</label><br>
    <br>
    <label for="name2">Masukkan nama orangtua/wali anda</label><br>
    <input type="text" id="name2" name="name2" value=" "><br>
    <br>
    <label for="address1">Masukkan alamat rumah anda</label><br>
    <input type="text" id="address1" name="address1"><br>
    <br>
    <label for="asal_sekolah">Masukkan asal sekolah anda</label><br>
    <input type="text" id="asal_sekolah" name="asal_sekolah"><br>
    <br>
    <label for="email1">Masukkan alamat email anda:</label><br>
    <input type="email" id="email1" name="email1" value=" "><br>
    <br>
    <label>Masukkan program studi yang anda ingin masuk</label><br>
    <input type="radio" id="kewirausahaan" name="prodi" value="Kewirausahaan">
    <label for="kewirausahaan">Kewirausahaan</label><br>
    <input type="radio" id="sistem_dan_teknologi_informasi" name="prodi" value="Sistem dan Teknologi Informasi">
    <label for="sistem_dan_teknologi_informasi">Sistem dan Teknologi Informasi</label><br>
    <input type="radio" id="bisnis_digital" name="prodi" value="Bisnis Digital">
    <label for="bisnis_digital">Bisnis_Digital</label><br>
    <br>
    <label>pilih pelajaran yang anda sukai</label><br>
    <input type="checkbox" id="sains" name="fav_subject" value="Sains">
    <label for="sains">Sains</label><br>
    <input type="checkbox" id="manajemen_bisnis" name="fav_subject" value="Manajemen Bisnis">
    <label for="manajemen_bisnis">Manajemen Bisnis</label><br>
    <input type="checkbox" id="komputer" name="fav_subject" value="Komputer">
    <label for="komputer">Komputer</label><br>
    <br>
    <label for="hobby">Tuliskan hobi anda</label><br>
    <input type="text" id="hobby" name="hobby"><br>
    <br>
    <input type="submit" value="Submit">
    </form>
  
</body>
