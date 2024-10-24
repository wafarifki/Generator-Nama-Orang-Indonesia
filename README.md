# Generator-Nama-Orang-Indonesia
Fungsi PHP untuk generate nama orang indonesia

# Cara Penggunaan
<p>Jalankan Perintah "composer require generator-nama-orang-indonesia" di git / gitbash. setelah itu add vendor/autoload</p>
<br>
<code>
require 'vendor/autoload.php'; // Autoload dari Composer

use GeneratorNama\NamaIndonesia;
$namaIndonesia = new NamaIndonesia();

// Generate satu nama acak
$namaAcak = $namaIndonesia->generateNamaLengkap();
echo "Nama acak: $namaAcak\n";

// Generate satu nama pria
$namaPria = $namaIndonesia->generateNamaLengkap('pria');
echo "Nama pria: $namaPria\n";

// Generate satu nama wanita
$namaWanita = $namaIndonesia->generateNamaLengkap('wanita');
echo "Nama wanita: $namaWanita\n";

// Generate daftar 20 nama acak
$daftarNama = $namaIndonesia->generateDaftarNama(20, 'random');
echo "\nDaftar 20 nama acak:\n";
echo implode("\n", $daftarNama);
</code>

# Let's connect with me!
<p>
    <a href="https://wafarifki.github.io" target="_blank"><img src="https://img.shields.io/badge/Website-https://wafarifki.github.io-blue?" /></a>
    <a href="https://wafarifki.com" target="_blank"><img src="https://img.shields.io/badge/Website-https://wafarifki.com-blue?" /></a>
    <a href="https://www.linkedin.com/in/wafarifqi" target="_blank"><img src="https://img.shields.io/badge/Linkedin-WafaRifkiAnafin_-blue" /></a>
    <a href="https://facebook.com/wafarifkianafin" target="_blank"><img src="https://img.shields.io/badge/Facebook-wafarifkianafin-blue" /></a>
    <a href="https://instagram.com/wafarifki_" target="_blank"><img src="https://img.shields.io/badge/Instagram-@wafarifki_-blue" /></a>
    <a href="https://github.com/wafarifki/wafarifki/raw/main/CV_WafaRifqiAnafin.pdf" target="_blank"><img src="https://img.shields.io/badge/Download-CV_-blue" /></a>
</p>
