<b>Aplikasi perentalan mobil</b><br>
<hr>
<h6>
    Aplikasi ini mempunyai fitur : 
</h6>
<ul>
        <li> data mobil</li>
        <li> data merk mobil</li>
        <li> data perentalan mobil</li>
        <li> Pembayaran DP</li>
        <li> Pengembalian Mobil</li>
        <li> Laporan Transaksi</li>
</ul>

Cara menjalankan Aplikasi : 
- Simpan Project di /htdocs (kalau pake xampp)
- git clone file yang ada digithub
- jalankan "composer install" di dalam terminal/cmd
- jalankan "npm install" di dalam terminal/cmd
- isi DB_DATABASE, DB_USERNAME, DB_PASSWORD, sesuaikan dengan settingan database kamu
- ketikan "php artisan key:generate" di terminal
- di dalam directory project buka terminal, ketikan "php artisan migrate"
- ketikan "php artisan serve" di terminal
