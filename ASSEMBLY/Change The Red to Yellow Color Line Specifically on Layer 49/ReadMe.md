# Berikut adalah tutorial langkah demi langkah untuk menjalankan program AutoLISP

### Langkah 1: Buka ZWCAD

Jalankan aplikasi ZWCAD di komputer.

### Langkah 2: Buka Editor LISP

Di ZWCAD, buka command line (biasanya di bagian bawah jendela).
Ketik VLIDE dan tekan Enter. Ini akan membuka Visual LISP Editor.

### Langkah 3: Salin Kode LISP
Salin kode [Change The Red to Yellow Color Line Specifically on Layer 49](https://github.com/NEAR07/Program-AutoLisp-ZWCAD-HullConstruction/blob/main/ASSEMBLY/Change%20The%20Red%20to%20Yellow%20Color%20Line%20Specifically%20on%20Layer%2049/LAYER49%20-%20Merubah%20garis%20warna%20merah%20ke%20kuning%20khusus%20di%20Layer%2049.lsp)

### Langkah 4: Tempel Kode ke Editor
Di Visual LISP Editor, buat file baru dengan memilih File > New.
Tempelkan kode yang telah di salin ke dalam jendela editor.

### Langkah 5: Simpan File
Simpan file dengan memilih File > Save As.
Beri nama file dengan ekstensi .lsp, misalnya Layer49.lsp.

### Langkah 6: Muat File LISP ke ZWCAD
Kembali ke jendela ZWCAD.
Ketik APPLOAD di command line dan tekan Enter.
Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.

### Langkah 7: Jalankan Perintah
Setelah file berhasil dimuat, Jalankan perintah dengan mengetik Layer49 di command line dan tekan Enter.
Program akan mencari semua objek di model space yang berada di layer "49" dan memiliki warna merah (warna 1), kemudian mengubah warnanya menjadi kuning (warna 60).

### Langkah 8: Verifikasi Hasil
Periksa objek di gambar untuk memastikan bahwa garis pada layer 49 yang sebelumnya berwarna merah telah berhasil diubah menjadi warna kuning.
