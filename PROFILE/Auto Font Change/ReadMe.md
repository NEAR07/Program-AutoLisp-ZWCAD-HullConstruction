# Berikut adalah tutorial langkah demi langkah untuk menjalankan program AutoLISP yang Anda berikan di ZWCAD:

### Langkah 1: Buka ZWCAD

Jalankan aplikasi ZWCAD di komputer Anda.

### Langkah 2: Buka Editor LISP

Di ZWCAD, buka command line (biasanya di bagian bawah jendela).
Ketik VLIDE dan tekan Enter. Ini akan membuka Visual LISP Editor.

### Langkah 3: Salin Kode LISP
Salin kode LISP 

### Langkah 4: Tempel Kode ke Editor
Di Visual LISP Editor, buat file baru dengan memilih File > New.
Tempelkan kode yang telah Anda salin ke dalam jendela editor.

### Langkah 5: Simpan File
Simpan file dengan memilih File > Save As.
Beri nama file dengan ekstensi .lsp, misalnya AFC.lsp.

### Langkah 6: Muat File LISP ke ZWCAD
Kembali ke jendela ZWCAD.
Ketik APPLOAD di command line dan tekan Enter.
Di jendela yang muncul, cari file .lsp yang telah Anda simpan dan klik Load.

### Langkah 7: Jalankan Perintah
Setelah file berhasil dimuat, Anda dapat menjalankan perintah dengan mengetik AFC di command line dan tekan Enter.
Program akan mencari semua objek teks (TEXT dan MTEXT) di gambar Anda dan mengubah gaya font mereka menjadi "AutoStyle" dengan ukuran font yang ditentukan.

### Langkah 8: Verifikasi Hasil
Periksa objek teks di gambar Anda untuk memastikan bahwa gaya font telah berubah sesuai dengan yang diinginkan.
