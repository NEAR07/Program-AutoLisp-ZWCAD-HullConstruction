# Berikut adalah tutorial langkah demi langkah untuk menjalankan program AutoLISP

### Langkah 1: Buka ZWCAD

Jalankan aplikasi ZWCAD di komputer.

### Langkah 2: Buka Editor LISP

Di ZWCAD, buka command line (biasanya di bagian bawah jendela).
Ketik VLIDE dan tekan Enter. Ini akan membuka Visual LISP Editor.

### Langkah 3: Salin Kode LISP
Salin kode [Rotation Text From 180 to 0 Degrees](https://github.com/NEAR07/Program-AutoLisp-ZWCAD/blob/main/PROFILE/Rotation%20Text%20From%20180%20to%200%20Degrees/RT0%20Rotation%20180%20to%200.lsp)

### Langkah 4: Tempel Kode ke Editor
Di Visual LISP Editor, buat file baru dengan memilih File > New.
Tempelkan kode yang telah di salin ke dalam jendela editor.

### Langkah 5: Simpan File
Simpan file dengan memilih File > Save As.
Beri nama file dengan ekstensi .lsp, misalnya RT0.lsp.

### Langkah 6: Muat File LISP ke ZWCAD
Kembali ke jendela ZWCAD.
Ketik APPLOAD di command line dan tekan Enter.
Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.

### Langkah 7: Jalankan Perintah
Setelah file berhasil dimuat, Jalankan perintah dengan mengetik RT0 di command line dan tekan Enter.
Program akan mencari semua objek teks (AcDbText) di model space yang memiliki rotasi 180 derajat dan mengubah rotasinya menjadi 0 derajat.

### Langkah 8: Verifikasi Hasil
Periksa objek teks di gambar untuk memastikan bahwa teks yang memiliki rotasi 180 derajat telah berhasil diubah menjadi 0 derajat.
Jika ada teks yang diubah, program akan menampilkan isi teks tersebut di command line.
