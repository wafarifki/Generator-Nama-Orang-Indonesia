# Generator-Nama-Orang-Indonesia
![PHP Version](https://img.shields.io/badge/php-%3E%3D%207.4-blue)
![License](https://img.shields.io/badge/license-MIT-green)

**Generator Nama Orang Indonesia** adalah library PHP yang memungkinkan Anda untuk menghasilkan nama-nama acak khas Indonesia. Anda dapat memilih nama pria, wanita, atau acak berdasarkan jenis kelamin.

## Fitur
- Generate nama lengkap pria.
- Generate nama lengkap wanita.
- Generate nama acak berdasarkan jenis kelamin.
- Generate daftar nama dalam jumlah yang diinginkan.

# Cara Penggunaan
<p>Jalankan Perintah "composer require generator-nama-orang-indonesia" di git / gitbash. setelah itu add vendor/autoload</p>
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
