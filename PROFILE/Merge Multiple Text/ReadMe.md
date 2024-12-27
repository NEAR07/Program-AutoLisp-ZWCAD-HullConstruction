# Berikut adalah tutorial langkah demi langkah untuk menjalankan program AutoLISP

### Langkah 1: Buka ZWCAD
Jalankan aplikasi ZWCAD di komputer.

### Langkah 2: Buka Editor LISP

Di ZWCAD, buka command line (biasanya di bagian bawah jendela).
Ketik VLIDE dan tekan Enter. Ini akan membuka Visual LISP Editor.

### Langkah 3: Salin Kode LISP
Salin kode [MTX Merge Text](https://github.com/NEAR07/Program-AutoLisp-ZWCAD/blob/main/PROFILE/Merge%20Multiple%20Text/MTX%20Merge%20Text.lsp)

### Langkah 4: Tempel Kode ke Editor
Di Visual LISP Editor, buat file baru dengan memilih File > New.
Tempelkan kode yang telah di salin ke dalam jendela editor.

### Langkah 5: Simpan File
Simpan file dengan memilih File > Save As.
Beri nama file dengan ekstensi .lsp, misalnya MTX.lsp.

### Langkah 6: Muat File LISP ke ZWCAD
Kembali ke jendela ZWCAD.
Ketik APPLOAD di command line dan tekan Enter.
Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.

### Langkah 7: Jalankan Perintah
Setelah file berhasil dimuat, Jalankan perintah dengan mengetik MTX di command line dan tekan Enter.
Program akan meminta untuk memilih teks yang terpisah-pisah. Pilih objek teks yang ingin gabungkan.

### Langkah 8: Verifikasi Hasil
Setelah Anda memilih teks, program akan menghapus teks yang terpisah dan menggabungkannya menjadi satu objek MTEXT dengan warna merah dan ukuran yang ditentukan.
Periksa hasilnya di gambar untuk memastikan bahwa teks telah berhasil digabung.