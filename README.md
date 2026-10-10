# Proyek Akuisisi dan Manajemen Data
Mata kuliah : BIFP-243 Akuisisi dan Manajemen Data

Nama / NIM  : Wilsa Dwi Amelia Hastiawan / 2501010009

Tujuan      : Memahami konsep Data Acquisition dan Data Management

## Struktur Folder
- data/raw        : data mentah hasil akuisisi (READ-ONLY)
- data/interim    : hasil antara (cleaning, transformasi)
- data/processed  : dataset final siap analisis
- notebooks       : notebook praktikum
- src             : script Python yang dapat digunakan ulang
- docs            : data dictionary dan metadata
- reports         : laporan kualitas data

## Cara Menjalankan Ulang
1. pip install -r requirements.txt
2. Jalankan notebook di folder notebooks secara berurutan

#

## Pentingnya reproducibility dalam akuisisi data dan contoh kasus nyatanya

Reproducibility penting dalam akuisisi data karena memastikan proses pengambilan dan pengolahan data dapat diulang oleh orang lain dengan langkah dan hasil yang sama atau mendekati sama. Dalam proses akuisisi data, sumber data, waktu pengambilan, kode program, library, struktur folder, serta perubahan terhadap data perlu didokumentasikan dengan baik. Tanpa reproducibility, hasil analisis akan sulit diperiksa dan kesalahan yang terjadi selama proses pengambilan data juga sulit dilacak. Penggunaan Git, README, notebook, dan struktur folder yang konsisten dapat membantu menyimpan riwayat perubahan serta menjelaskan tahapan yang dilakukan. Salah satu contoh nyata adalah pengambilan data harga produk dari sebuah website menggunakan program Python. Jika program, tanggal pengambilan data, sumber website, dan proses pembersihan data tidak dicatat, orang lain akan kesulitan mendapatkan hasil yang sama karena harga pada website dapat berubah. Sebaliknya, jika seluruh proses terdokumentasi dan kode disimpan menggunakan Git, proses tersebut dapat dijalankan kembali sehingga hasilnya lebih mudah diverifikasi. Oleh karena itu, reproducibility sangat penting untuk menjaga transparansi, konsistensi, dan kepercayaan terhadap hasil pengolahan data.
