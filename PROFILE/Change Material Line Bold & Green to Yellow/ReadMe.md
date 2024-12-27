# Berikut adalah tutorial langkah demi langkah untuk menjalankan program AutoLISP

### Langkah 1: Buka ZWCAD
Jalankan aplikasi ZWCAD di komputer.

### Langkah 2: Buka Editor LISP

Di ZWCAD, buka command line (biasanya di bagian bawah jendela).
Ketik VLIDE dan tekan Enter. Ini akan membuka Visual LISP Editor.

### Langkah 3: Salin Kode LISP
Salin kode [MLY Material Line Bold & Green to Yellow](https://github.com/NEAR07/Program-AutoLisp-ZWCAD/blob/main/PROFILE/Change%20Material%20Line%20Bold%20%26%20Green%20to%20Yellow/MLY%20Material%20Line%20Bold%20%26%20Green%20to%20Yellow.lsp)

### Langkah 4: Tempel Kode ke Editor
Di Visual LISP Editor, buat file baru dengan memilih File > New.
Tempelkan kode yang telah di salin ke dalam jendela editor.

### Langkah 5: Simpan File
Simpan file dengan memilih File > Save As.
Beri nama file dengan ekstensi .lsp, misalnya MLY.lsp.

### Langkah 6: Muat File LISP ke ZWCAD
Kembali ke jendela ZWCAD.
Ketik APPLOAD di command line dan tekan Enter.
Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.

### Langkah 7: Jalankan Perintah
Setelah file berhasil dimuat, Jalankan perintah dengan mengetik MLY di command line dan tekan Enter.
Program akan mencari semua polyline berwarna hijau (warna 3) dan mengubahnya menjadi kuning (warna 2). Selain itu, program juga akan mempertebal lineweight polyline yang sudah berwarna kuning.

### Langkah 8: Verifikasi Hasil
Periksa objek polyline di gambar untuk memastikan bahwa warna dan lineweight telah berubah sesuai dengan yang diinginkan.
