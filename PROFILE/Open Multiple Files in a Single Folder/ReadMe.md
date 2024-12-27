# Berikut adalah tutorial langkah demi langkah untuk menjalankan program AutoLISP di ZWCAD

### Langkah 1: Buka ZWCAD
Jalankan aplikasi ZWCAD di komputer.

### Langkah 2: Buka Editor LISP
Di ZWCAD, buka command line (biasanya di bagian bawah jendela).
Ketik VLIDE dan tekan Enter. Ini akan membuka Visual LISP Editor.

### Langkah 3: Salin Kode LISP
Salin seluruh kode LISP yang berikan, termasuk semua fungsi yang ada di dalamnya.

### Langkah 4: Tempel Kode ke Editor
Di Visual LISP Editor, buat file baru dengan memilih File > New.
Tempelkan kode yang telah di salin ke dalam jendela editor.

### Langkah 5: Simpan File
Simpan file dengan memilih File > Save As.
Beri nama file dengan ekstensi .lsp, misalnya MyLISPProgram.lsp.

### Langkah 6: Muat File LISP ke ZWCAD
Kembali ke jendela ZWCAD.
Ketik APPLOAD di command line dan tekan Enter.
Di jendela yang muncul, cari file .lsp yang telah di simpan dan klik Load.

### Langkah 7: Jalankan Perintah CMB1CSV
Setelah file berhasil dimuat, Jalankan perintah pertama dengan mengetik CMB1CSV di command line dan tekan Enter.
Program akan meminta untuk memilih direktori yang berisi file DXF yang ingin dipindai.
Setelah memilih direktori, program akan meminta untuk memilih file CSV (database-profile.csv) yang akan digunakan untuk pengurutan.
Program akan memproses file DXF yang sesuai dengan nama yang ada di file CSV dan menginsernya ke dalam gambar.

### Langkah 8: Jalankan Perintah MBB
Setelah perintah CMB1CSV selesai, jalankan perintah kedua dengan mengetik MBB di command line dan tekan Enter.
Program akan meminta untuk memilih file CSV (database-profile.csv) lagi.
Program akan mencari semua blok yang ada di gambar dan mengelompokkannya berdasarkan nama yang ada di file CSV.
   
### Langkah 9: Jalankan Perintah MBBCSV
Setelah perintah MBB selesai, jalankan perintah ketiga dengan mengetik MBBCSV di command line dan tekan Enter.
Program akan meminta untuk memilih file CSV (database-profile.csv) sekali lagi.
Program akan mencari semua blok yang ada di gambar, mengelompokkannya berdasarkan nama yang ada di file CSV, dan menambahkan judul kelompok di atas setiap kelompok blok.

### Langkah 10: Verifikasi Hasil
Periksa gambar untuk memastikan bahwa semua blok telah diproses sesuai dengan yang diinginkan.
Pastikan bahwa semua blok yang sesuai dengan nama di file CSV telah diinsert dan dikelompokkan dengan benar.
